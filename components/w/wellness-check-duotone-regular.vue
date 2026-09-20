<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="gsqg19bkd"/><path class="c1m5481ki"/><path class="z7796cdhw"/><path class="yok9qsxfg"/><path class="rm9_1_hyj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:wellness-check-duotone-regular" /></template>
<style>
.c1m5481ki {
  fill: currentColor;
  d: path("M16 16a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.gsqg19bkd {
  fill: currentColor;
  d: path("M3 12a3.5 3.5 0 0 1 7 0 3.5 3.5 0 0 1 7 0l-7 7Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rm9_1_hyj {
  d: path("M16 16a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.yok9qsxfg {
  d: path("M19 8v5");
}

.z7796cdhw {
  d: path("M3 12a3.5 3.5 0 0 1 7 0 3.5 3.5 0 0 1 7 0l-7 7Z");
}

</style>
