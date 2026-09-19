<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g2wj9jbhp"/><path class="b9vcbob5z"/><path class="yed56cb1q"/><path class="agekjmvhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mi-canvas" /></template>
<style>
.agekjmvhk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m42.174 8.546l-4.93 8.539c-.416.72-1.33.964-2.05.549l-.207-.12a1.497 1.497 0 0 1-.55-2.05l5.475-9.482M5.873 12.603c6.006-1.33 15.533.682 15.751 6.888c.185 5.237-9.363 7.232-9.616 11.586c-.25 4.295 5.798 5.94 12.498 5.123");
}

.b9vcbob5z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.512 32.887a3.1 3.1 0 0 1-1.553-.418a3.1 3.1 0 0 1-1.139-1.135");
}

.g2wj9jbhp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 5.5h29c2.216 0 4 1.784 4 4v29c0 2.216-1.784 4-4 4h-29c-2.216 0-4-1.784-4-4v-29c0-2.216 1.784-4 4-4");
}

.yed56cb1q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m42.329 15.67l-3.103 5.373C37.82 23.48 36 25.687 34.012 27.675l-8.64 8.64c-.259.259-1.045-.195-.95-.549l3.162-11.801c.728-2.717 1.73-5.397 3.136-7.833l6.04-10.46");
}

</style>
