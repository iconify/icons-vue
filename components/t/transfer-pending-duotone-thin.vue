<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pt9gscciw"/><path class="mcubrkb2y"/><path class="odj5t8eez"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:transfer-pending-duotone-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mcubrkb2y {
  d: path("M2 21h20M5 21V9m14 12V9M2 9h20M5 9l5.5 -5.5h3L19 9");
}

.odj5t8eez {
  d: path("M9.5 12.5h5l-5 5h5Z");
}

.pt9gscciw {
  fill: currentColor;
  d: path("M9.5 12.5h5l-5 5h5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
