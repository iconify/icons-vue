<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="m5_qrrbwf"/><path class="dzsv_bjnw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:sliders-horizontal-sharp-duotone" /></template>
<style>
.dzsv_bjnw {
  d: path("M16 2L16 8M10 9L10 15M14 16L14 22");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.m5_qrrbwf {
  stroke-opacity: 0.4;
  d: path("M2 5L13 5M22 5L16 5M2 12L10 12M22 12L13 12M2 19L11 19M22 19L14 19");
}

</style>
