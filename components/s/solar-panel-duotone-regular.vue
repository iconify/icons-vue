<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vn6-6774p"/><path class="s1r4963pp"/><path class="s09hy0b0y"/><path class="wcigoab1j"/><path class="m0f5ny81l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:solar-panel-duotone-regular" /></template>
<style>
.m0f5ny81l {
  d: path("M5 20h8");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.s09hy0b0y {
  d: path("M7 11h10");
}

.s1r4963pp {
  d: path("m4 14 6 -6h10l-6 6Z");
}

.vn6-6774p {
  fill: currentColor;
  d: path("m4 14 6 -6h10l-6 6Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.wcigoab1j {
  d: path("M9 14v6");
}

</style>
