<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rsr2n-zcx"/><path class="c_ivw10tn"/><path class="ri8hejbxk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:occupancy-rate" /></template>
<style>
.c_ivw10tn {
  d: path("M4.5 8.5V20h6.1m6.4-9.8V8.5m-4 9a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ri8hejbxk {
  fill: currentColor;
  d: path("M17.5 17.5v-1.75a1.75 1.75 0 1 0 1.75 1.75Z");
}

.rsr2n-zcx {
  d: path("m2.5 10l8.25-7L19 10");
}

</style>
