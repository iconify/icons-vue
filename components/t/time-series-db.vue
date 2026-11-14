<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fg8nb-p7y"/><path class="pe9068s_v"/><path class="jtlp82emg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:time-series-db" /></template>
<style>
.fg8nb-p7y {
  d: path("M3.5 3v17.5H12");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jtlp82emg {
  d: path("M15 16v4a3.5 1.5 0 0 0 7 0v-4");
}

.pe9068s_v {
  d: path("m6.5 15.5l3.5-4l3 2l6.5-8M15 16a3.5 1.5 0 1 0 7 0a3.5 1.5 0 1 0-7 0");
}

</style>
