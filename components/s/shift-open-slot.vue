<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wocaxlmgc"/><path class="guzy0jblx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:shift-open-slot" /></template>
<style>
.guzy0jblx {
  d: path("M8 13.5V12h1.5m5 0H16v1.5m0 5V20h-1.5m-5 0H8v-1.5m3.25-6.5h1.5m-1.5 8h1.5M8 15.25v1.5m8-1.5v1.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wocaxlmgc {
  d: path("M3 4.5h18v17H3Zm5-2v4m8-4v4m-13 3h18");
}

</style>
