<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="oe_q4780g"/><circle class="c55ag9btm"/><path class="roh-o2f0v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:music-note-2-linear" /></template>
<style>
.c55ag9btm {
  cx: 9px;
  cy: 18px;
  r: 4px;
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oe_q4780g {
  d: path("M13 18V10V2");
}

.roh-o2f0v {
  d: path("M19 8C15.6863 8 13 5.31371 13 2");
}

</style>
