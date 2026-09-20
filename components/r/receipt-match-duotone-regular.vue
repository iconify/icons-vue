<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ots31sbwo"/><path class="ryrxl6ewx"/><path class="frhoh0utb"/><path class="jd_dotbnq"/><path class="fn5bvibgl"/><path class="eja300fqs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:receipt-match-duotone-regular" /></template>
<style>
.eja300fqs {
  d: path("M11.5 10a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.fn5bvibgl {
  d: path("M8.5 10a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.frhoh0utb {
  fill: currentColor;
  d: path("M11.5 10a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.jd_dotbnq {
  d: path("M6 2h12a2 2 0 0 1 2 2v15l-2 -2 -2 2 -2 -2 -2 2 -2 -2 -2 2 -2 -2 -2 2V4a2 2 0 0 1 2 -2");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ots31sbwo {
  fill: currentColor;
  d: path("M6 2h12a2 2 0 0 1 2 2v15l-2 -2 -2 2 -2 -2 -2 2 -2 -2 -2 2 -2 -2 -2 2V4a2 2 0 0 1 2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ryrxl6ewx {
  fill: currentColor;
  d: path("M8.5 10a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
