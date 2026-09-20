<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="knkoaqoew"/><path class="d7nzp-bmn"/><path class="tgj7e4byf"/><path class="bn3zbuwch"/><path class="xxobs597t"/><path class="nancp9ugm"/><path class="rgnpgnbjr"/><path class="fttf_kblh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:speech-recognize-duotone-regular" /></template>
<style>
.bn3zbuwch {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M16 14h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.d7nzp-bmn {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5.05 16.95a7 7 0 0 1 0 -9.9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.fttf_kblh {
  d: path("M16 14h5");
}

.knkoaqoew {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7.88 14.12a3 3 0 0 1 0 -4.24");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nancp9ugm {
  d: path("M5.05 16.95a7 7 0 0 1 0 -9.9");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rgnpgnbjr {
  d: path("M16 10h5");
}

.tgj7e4byf {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M16 10h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xxobs597t {
  d: path("M7.88 14.12a3 3 0 0 1 0 -4.24");
}

</style>
