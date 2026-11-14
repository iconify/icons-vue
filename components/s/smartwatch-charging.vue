<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c87_qgboq"/><path class="cmqbn4brm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:smartwatch-charging" /></template>
<style>
.c87_qgboq {
  d: path("M11.25 6h1.5A5.25 5.25 0 0 1 18 11.25v1.5A5.25 5.25 0 0 1 12.75 18h-1.5A5.25 5.25 0 0 1 6 12.75v-1.5A5.25 5.25 0 0 1 11.25 6M8.5 6L9 3h6l.5 3m-7 12l.5 3h6l.5-3");
}

.cmqbn4brm {
  d: path("m12.75 8.5l-2 3.5h2.5l-2 3.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
