<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bya5chhbw"/><path class="n740cbb0b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:page-curl" /></template>
<style>
.bya5chhbw {
  d: path("M6 2.5h12a2 2 0 0 1 2 2V13l-8 8.5H6a2 2 0 0 1-2-2v-15a2 2 0 0 1 2-2");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n740cbb0b {
  d: path("M20 13q-8 0-8 8.5M7.5 7h9");
}

</style>
