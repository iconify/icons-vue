<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="vykljl53m"/><path class="vxfblzezi"/><path class="x90qxybzn"/><path class="vlpopjb9t"/><path class="zn9hxbcae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:microsoft-teams" /></template>
<style>
.vlpopjb9t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.35 18.5h8.3m-4.15 11v-11");
}

.vxfblzezi {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  d: path("M33.46 35.73a4 4 0 0 0 1.28.79a6.42 6.42 0 0 0 8.76-6v-9.38a1.75 1.75 0 0 0-1.72-1.76h-9.36m-8.05-1.88s1.07-.17 1.42-.25a5.89 5.89 0 0 0 3.92-7.55A6 6 0 0 0 18 11.52a6.2 6.2 0 0 0 .15 1.36l.28 1.12");
}

.vykljl53m {
  cx: 37.07px;
  cy: 13.19px;
  r: 4.16px;
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
}

.x90qxybzn {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  d: path("M14 34a16 16 0 0 0 .55 2.07A10.5 10.5 0 0 0 24 42.5a10.43 10.43 0 0 0 10.12-10.67V21.16a1.74 1.74 0 0 0-1.7-1.78h-8");
}

.zn9hxbcae {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  d: path("M4.5 16v16a2 2 0 0 0 2 2h16a2 2 0 0 0 2-2V16a2 2 0 0 0-2-2h-16a2 2 0 0 0-2 2Z");
}

</style>
