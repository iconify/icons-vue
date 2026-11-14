<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tium3acay"/><path class="djzdsds_o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sleeping-bag-rating" /></template>
<style>
.djzdsds_o {
  d: path("M6.25 7.75a2.75 2 0 1 0 5.5 0a2.75 2 0 1 0-5.5 0m12.5 8v6m-2.5-4.5l5 3m-5 0l5-3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tium3acay {
  d: path("M9 2.5c4 0 5.5 2.5 5.5 6L13 20a2 2 0 0 1-2 1.5H7A2 2 0 0 1 5 20L3.5 8.5c0-3.5 1.5-6 5.5-6");
}

</style>
