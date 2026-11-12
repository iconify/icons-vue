<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="zmtfhxbuo"/><path class="zgohmrbgb"/><path class="qy9-4uicp"/><path class="jl627cb0x"/><path class="xdc5sacat"/><path class="epk2vguqy"/><path class="zhsko8bvk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:tram-line-duotone" /></template>
<style>
.epk2vguqy {
  stroke-linejoin: round;
  d: path("M17 20L18 22");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jl627cb0x {
  stroke-linejoin: round;
  d: path("M7 16H8.5");
}

.qy9-4uicp {
  stroke-linejoin: round;
  d: path("M15.5 16H17");
}

.xdc5sacat {
  stroke-linejoin: round;
  d: path("M7 20L6 22");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.zgohmrbgb {
  stroke-linejoin: round;
  d: path("M4 13H20");
}

.zhsko8bvk {
  stroke-linejoin: round;
  d: path("M10 2V2.5C10 3.60457 10.8954 4.5 12 4.5C13.1046 4.5 14 3.60457 14 2.5V2");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.zmtfhxbuo {
  d: path("M12 20C8.22876 20 6.34315 20 5.17157 18.8284C4 17.6569 4 15.7712 4 12V10C4 6.22876 4 4.34315 5.17157 3.17157C6.34315 2 8.22876 2 12 2C15.7712 2 17.6569 2 18.8284 3.17157C20 4.34315 20 6.22876 20 10V12C20 15.7712 20 17.6569 18.8284 18.8284C17.6569 20 15.7712 20 12 20Z");
}

</style>
