<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="brv9vib3d"/><path class="zfk_4da5x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pansy" /></template>
<style>
.brv9vib3d {
  d: path("M12 6a3.75 3.75 0 1 1 5.25 4a3 3 0 1 1-1 5a4.25 4.25 0 0 1-8.5 0a3 3 0 1 1-1-5A3.75 3.75 0 1 1 12 6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zfk_4da5x {
  fill: currentColor;
  d: path("M10.5 11.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

</style>
