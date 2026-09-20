<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m2iblkrmn"/><path class="kn-4tic2i"/><path class="t8qnl-bvo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:page-turn-duotone-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kn-4tic2i {
  d: path("M4 21V3h10l6 6v12Z");
}

.m2iblkrmn {
  fill: currentColor;
  d: path("M4 21V3h10l6 6v12Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.t8qnl-bvo {
  d: path("M14 3v6h6");
}

</style>
