<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tmwz_qbnn"/><path class="ntrlozbny"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mine-tunnel" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ntrlozbny {
  fill: currentColor;
  d: path("M9.5 20.5v-4a2.5 2.5 0 0 1 5 0v4Z");
}

.tmwz_qbnn {
  d: path("M2 13c2-6 6-9.5 10-9.5S20 7 22 13M2 20.5h20M6 11h12M6.75 11v9.5m10.5-9.5v9.5");
}

</style>
