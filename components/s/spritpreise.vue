<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dm2nieb8t"/><path class="o42506b8w"/><path class="j-cijpj0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:spritpreise" /></template>
<style>
.dm2nieb8t {
  fill: none;
  stroke: currentColor;
  d: path("M21.96 9.52c-.022-2.097.788-2.468 2.668-2.468h10.653c1.751 0 2.281.737 2.281 2.468v8.14c0 1.77-.497 2.302-2.28 2.302H24.627c-1.895 0-2.667-.524-2.667-2.301z");
}

.j-cijpj0i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.309 8.198h-1.385c-.454 0-1.011.224-1.439 1.1c-.428.875-.878 2.557-.878 2.557v3.873h3.722v25.06h1.94V43.5h16.955v-2.712h1.899V6.255c0-1.036-.504-1.755-1.672-1.755H20.956c-1.115 0-1.647.605-1.647 1.755z");
}

.o42506b8w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.804 15.79v22.838c0 3.68-2.766 4.601-4.601 4.601s-4.48-1.7-4.319-4.319c.24-3.888 1.751-4.441 5.886-13.362c3.473-7.493 3.034-9.759 3.034-9.759z");
}

</style>
