<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="h5spufblj"/><path class="xdo0cdc_m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:plug-off-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.h5spufblj {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M6.177 15.823A2 2 0 0 1 6 15V9a2.003 2.003 0 0 1 2-2h7ZM18 10v5a2.003 2.003 0 0 1-2 2h-5Z");
}

.xdo0cdc_m {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 16V9a2 2 0 0 1 2-2h7m3 3v5a2 2 0 0 1-2 2h-5m1 0v4M9 3v4m6-4v4M2 20L20 2");
}

</style>
