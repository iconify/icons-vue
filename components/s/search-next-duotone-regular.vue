<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="g7od41byc"/><path class="p367mshbv"/><path class="rseiusb3q"/><path class="jtt8g10_o"/><path class="c_tajwbcn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:search-next-duotone-regular" /></template>
<style>
.c_tajwbcn {
  d: path("M12.5 7.5 15 10l-2.5 2.5");
}

.g7od41byc {
  fill: currentColor;
  d: path("M5.5 10a6.5 6.5 0 1 0 13 0 6.5 6.5 0 1 0 -13 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.jtt8g10_o {
  d: path("M9 10h6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p367mshbv {
  d: path("M5.5 10a6.5 6.5 0 1 0 13 0 6.5 6.5 0 1 0 -13 0");
}

.rseiusb3q {
  d: path("M16.5 14.5 21 19");
}

</style>
