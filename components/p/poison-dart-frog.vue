<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tztervpiu"/><path class="k4iawsbjq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:poison-dart-frog" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k4iawsbjq {
  d: path("M6.25 8L3.5 6V3.5M14.75 8l2.75-2V3.5M6.5 14l-3 2l1 3M8.75 7.5h.01m3.49 0h.01M15.5 21l5.5-5.5m-3 0h3v3m-6 1l2 2");
}

.tztervpiu {
  d: path("M5.5 10.75a5 6.25 0 1 0 10 0a5 6.25 0 1 0-10 0");
}

</style>
