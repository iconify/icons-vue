<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="zn4ls_gfh"/><path class="j0myhvb1y"/><circle class="c6a_l3n8b"/><circle class="q56bcj7au"/><path class="z74fryb4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sparkasse-george" /></template>
<style>
.c6a_l3n8b {
  cx: 16.725px;
  cy: 33.975px;
  r: 1.552px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.j0myhvb1y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.24 38.22h7.162m-9.341 2.694h7.162");
}

.q56bcj7au {
  cx: 24px;
  cy: 16.439px;
  r: 11.939px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.z74fryb4n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.939 31.561A11.94 11.94 0 0 1 24 43.5");
}

.zn4ls_gfh {
  width: 9.341px;
  height: 8.081px;
  x: 12.061px;
  y: 35.527px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.552px;
}

</style>
