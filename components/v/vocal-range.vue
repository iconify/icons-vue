<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="asvo2k6jy"/><path class="rjwyi07aa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:vocal-range" /></template>
<style>
.asvo2k6jy {
  d: path("M9.5 2.5za3 3 0 0 1 3 3V11a3 3 0 0 1-3 3a3 3 0 0 1-3-3V5.5a3 3 0 0 1 3-3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rjwyi07aa {
  d: path("M3 11a6.5 6.5 0 0 0 13 0m-6.5 6.5v4m6.75-4l2.25-2.25l2.25 2.25m-2.25-2.25v6.5m-2.25-2.25l2.25 2.25l2.25-2.25");
}

</style>
