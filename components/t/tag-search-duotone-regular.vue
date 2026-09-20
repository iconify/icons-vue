<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ls5w73s4p"/><path class="bij68h4ua"/><path class="rmac01ujx"/><path class="fau57ihtk"/><path class="meyucufno"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:tag-search-duotone-regular" /></template>
<style>
.bij68h4ua {
  fill: currentColor;
  d: path("M15 10a3.5 3.5 0 1 0 7 0 3.5 3.5 0 1 0 -7 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.fau57ihtk {
  d: path("M15 10a3.5 3.5 0 1 0 7 0 3.5 3.5 0 1 0 -7 0");
}

.ls5w73s4p {
  fill: currentColor;
  d: path("M3 6h5l4 4 -4 4H3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.meyucufno {
  d: path("m16 12.5 -2 2");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rmac01ujx {
  d: path("M3 6h5l4 4 -4 4H3Z");
}

</style>
