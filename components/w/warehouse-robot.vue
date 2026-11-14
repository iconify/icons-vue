<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="h05rvwb-u"/><path class="nlx1v7bjk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:warehouse-robot" /></template>
<style>
.h05rvwb-u {
  d: path("M6 9h12v9H6Zm6 0V5.5m0-1h.01");
}

.nlx1v7bjk {
  d: path("M8.5 13a1 1 0 1 0 2 0a1 1 0 1 0-2 0Zm5 0a1 1 0 1 0 2 0a1 1 0 1 0-2 0ZM7 20a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm7 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
