<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="dq95syblc"/><rect transform="rotate(175.825 27.436 24.012)" class="t3drjo-fc"/><path class="m4g6z8cox"/><circle class="fvy1281yv"/><path class="e3pfwv8jv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:migu" /></template>
<style>
.dq95syblc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m11.572 28.149l-.654-8.965l5.142 8.647l3.833-9.288l.654 8.96m8.916-6.627l.49 6.73a2.25 2.25 0 0 1-2.079 2.408a2.24 2.24 0 0 1-1.634-.542");
}

.e3pfwv8jv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m22.544 21.381l.434 5.945");
}

.fvy1281yv {
  cx: 22.344px;
  cy: 18.632px;
  r: 0.75px;
  fill: currentColor;
}

.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.m4g6z8cox {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m31.997 20.69l.27 3.703a2.25 2.25 0 1 0 4.487-.328l-.27-3.702m.27 3.702l.164 2.243");
}

.t3drjo-fc {
  width: 4.499px;
  height: 5.961px;
  x: 25.186px;
  y: 21.032px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.249px;
  ry: 2.249px;
}

</style>
