<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="uw2j_fbcl"/><path class="bpzoyz92y"/><path class="gqph8sbcu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:metric-sparkline-card" /></template>
<style>
.bpzoyz92y {
  fill: currentColor;
  d: path("M6 7.75h7v2.5H6Z");
}

.gqph8sbcu {
  d: path("m6 16l2.5-2.5L11 15l2.5-3.25l2.5 1.5L18 11");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uw2j_fbcl {
  d: path("M3.5 4.5h17a1 1 0 0 1 1 1v13a1 1 0 0 1-1 1h-17a1 1 0 0 1-1-1v-13a1 1 0 0 1 1-1Z");
}

</style>
