<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="aqw2k7gkz"/><path class="r0m5_4qma"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sold-sign" /></template>
<style>
.aqw2k7gkz {
  d: path("M3.5 21.5v-19m0 2.5h17M9.125 7.5h8.25A2.625 2.625 0 0 1 20 10.125v5.75a2.625 2.625 0 0 1-2.625 2.625h-8.25A2.625 2.625 0 0 1 6.5 15.875v-5.75A2.625 2.625 0 0 1 9.125 7.5M9 5v2.5M17.5 5v2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r0m5_4qma {
  fill: currentColor;
  d: path("m6.92 14.064l5.888-6.105a1.5 1.5 0 0 1 1.079-.459h1.238a.802.802 0 0 1 .58 1.356l-7.824 8.197A.801.801 0 0 1 6.5 16.5v-1.395a1.5 1.5 0 0 1 .42-1.041");
}

</style>
