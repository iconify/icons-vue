<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n6rtbwb2x"/><path class="g5h9wlbtb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:virtual-machine-code" /></template>
<style>
.g5h9wlbtb {
  d: path("M11.341 9.077za.564.564 0 0 1 .563-.522h.192a.564.564 0 0 1 .563.522a.99.99 0 0 0 .492.784l.126.073a.99.99 0 0 0 .925.034a.564.564 0 0 1 .733.226l.096.167a.564.564 0 0 1-.171.748a.99.99 0 0 0-.432.818v.146a.99.99 0 0 0 .432.818a.564.564 0 0 1 .171.748l-.096.167a.564.564 0 0 1-.733.226a.99.99 0 0 0-.925.034l-.126.073a.99.99 0 0 0-.492.784a.564.564 0 0 1-.563.522h-.192a.564.564 0 0 1-.563-.522a.99.99 0 0 0-.492-.784l-.126-.073a.99.99 0 0 0-.925-.034a.564.564 0 0 1-.733-.226l-.096-.167a.564.564 0 0 1 .171-.748a.99.99 0 0 0 .432-.818v-.146a.99.99 0 0 0-.432-.818a.564.564 0 0 1-.171-.748l.096-.167a.564.564 0 0 1 .733-.226a.99.99 0 0 0 .925-.034l.126-.073a.99.99 0 0 0 .492-.784M2.5 9.5h3m-3 5h3m13-5h3m-3 5h3m-12-12v3m5-3v3m-5 13v3m5-3v3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n6rtbwb2x {
  d: path("M9.875 5.5h4.25A4.375 4.375 0 0 1 18.5 9.875v4.25a4.375 4.375 0 0 1-4.375 4.375h-4.25A4.375 4.375 0 0 1 5.5 14.125v-4.25A4.375 4.375 0 0 1 9.875 5.5");
}

</style>
