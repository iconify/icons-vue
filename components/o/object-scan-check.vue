<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m83utt8qd"/><path class="uh2hvuu2o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:object-scan-check" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m83utt8qd {
  d: path("M3 7.5V3h4.5m9 0H21v4.5m-18 9V21h4.5m4.728-14.595l3 1.666A1.5 1.5 0 0 1 16 9.383v3.234a1.5 1.5 0 0 1-.772 1.312l-3 1.666a1.5 1.5 0 0 1-1.456 0l-3-1.666A1.5 1.5 0 0 1 7 12.617V9.383a1.5 1.5 0 0 1 .772-1.312l3-1.666a1.5 1.5 0 0 1 1.456 0");
}

.uh2hvuu2o {
  d: path("m7 8.5l4.5 2.5L16 8.5M11.5 11v5m3.25 2l2 2L21 15.75");
}

</style>
