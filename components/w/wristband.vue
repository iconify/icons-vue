<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zr80cmz_x"/><path class="ry733bbts"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:wristband" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ry733bbts {
  d: path("M6 8.25a6 1.25 0 1 0 12 0a6 1.25 0 1 0-12 0m2 4.5v4.5M12 13v4.5m4-4.75v4.5");
}

.zr80cmz_x {
  d: path("M3 8a9 4 0 0 1 18 0v8a9 4 0 0 1-18 0Z");
}

</style>
