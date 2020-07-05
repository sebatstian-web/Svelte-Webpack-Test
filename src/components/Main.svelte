<style>
  .Main {
    display: grid;
    grid-template-columns: minmax(auto, 1024px);
    justify-content: center;
    align-items: center;
  }
</style>

<div class="Main">
  <!-- 
    slot es palabra reservada en Svelte para la manipulación de 
    componentes hijos
  -->
  <slot />
</div>