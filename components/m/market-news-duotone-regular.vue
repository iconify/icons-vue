<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="g7d56fjnv"/><path class="u079x8b6x"/><path class="vyks9vbfn"/><path class="gla11n-mx"/><path class="cx8rytfxu"/><path class="l1lmw_bdv"/><path class="r96yn6b-w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:market-news-duotone-regular" /></template>
<style>
.cx8rytfxu {
  d: path("M13 8h6");
}

.g7d56fjnv {
  fill: currentColor;
  d: path("M2 6a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.gla11n-mx {
  d: path("M5 8h5v5H5Z");
}

.l1lmw_bdv {
  d: path("M13 11h6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.r96yn6b-w {
  d: path("M5 16.5h14");
}

.u079x8b6x {
  fill: currentColor;
  d: path("M5 8h5v5H5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.vyks9vbfn {
  d: path("M2 6a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

</style>
