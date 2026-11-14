<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="buyorrbvx"/><path class="rpec4bc-f"/><path class="rh_2n9bch"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:thermometer-sun" /></template>
<style>
.buyorrbvx {
  d: path("M13.75 12.5v-7a3 3 0 0 1 6 0v7a5 5 0 1 1-6 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rh_2n9bch {
  d: path("M4.5 6.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m2-3.5V2m0 8v1M3 6.5H2m8 0h1M4 4l-.75-.75M9 4l.75-.75M4 9l-.75.75M9 9l.75.75");
}

.rpec4bc-f {
  fill: currentColor;
  d: path("M14.75 16.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

</style>
