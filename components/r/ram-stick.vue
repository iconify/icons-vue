<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e3yyqeblq"/><path class="khw6n_bkq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ram-stick" /></template>
<style>
.e3yyqeblq {
  d: path("M5.125 5.5h13.75A2.625 2.625 0 0 1 21.5 8.125v3.75a2.625 2.625 0 0 1-2.625 2.625H5.125A2.625 2.625 0 0 1 2.5 11.875v-3.75A2.625 2.625 0 0 1 5.125 5.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.khw6n_bkq {
  d: path("M7 8.25h1.5a1.5 1.5 0 0 1 1.5 1.5v.5a1.5 1.5 0 0 1-1.5 1.5H7a1.5 1.5 0 0 1-1.5-1.5v-.5A1.5 1.5 0 0 1 7 8.25m8.5 0H17a1.5 1.5 0 0 1 1.5 1.5v.5a1.5 1.5 0 0 1-1.5 1.5h-1.5a1.5 1.5 0 0 1-1.5-1.5v-.5a1.5 1.5 0 0 1 1.5-1.5m-10 6.25V18m3-3.5V18m3-3.5V18m4-3.5V18m3-3.5V18");
}

</style>
