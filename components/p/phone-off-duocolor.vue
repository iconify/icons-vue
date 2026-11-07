<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wfztb1bqh"/><path class="vik52tb2d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:phone-off-duocolor" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vik52tb2d {
  d: path("M7.686 16.314A15.95 15.95 0 0 1 3 5a2 2 0 0 1 2-2h3c.995 0 1.8.403 2 1l1 3c.153.46-.234 1.234-1 2l-1 1a1.414 1.414 0 0 0 0 2l1.5 1.5M17 13l3 1c.597.2 1 1.005 1 2v3a2 2 0 0 1-2 2c-2.878 0-5.578-.76-7.91-2.09");
}

.wfztb1bqh {
  stroke-opacity: 0.4;
  d: path("M2 22L22 2");
}

</style>
