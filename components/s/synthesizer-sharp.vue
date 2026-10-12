<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="hbk_ml_rq"/><path class="kp26debrw"/><path class="dsy8v2brp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:synthesizer-sharp" /></template>
<style>
.dsy8v2brp {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.25 8.25h4.5");
}

.hbk_ml_rq {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 5.75h18.5v12.5H2.75zm0 5h18.5m-13.85 0v7.5m4.6-7.5v7.5m4.6-7.5v7.5");
}

.kp26debrw {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.25 8.25h.01m3.24 0h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
