<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x1h03bbsr"/><path class="bo77nacip"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pedestal-camera" /></template>
<style>
.bo77nacip {
  d: path("M16.829 5.085L18 4.5a1.382 1.382 0 0 1 2 1.236v2.028A1.382 1.382 0 0 1 18 9l-1.171-.585A1.5 1.5 0 0 1 16 7.073v-.646a1.5 1.5 0 0 1 .829-1.342M10 10.5v11m0-7.5l-5 7.5m5-7.5l5 7.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x1h03bbsr {
  d: path("M6.625 3h6.75A2.625 2.625 0 0 1 16 5.625v2.25a2.625 2.625 0 0 1-2.625 2.625h-6.75A2.625 2.625 0 0 1 4 7.875v-2.25A2.625 2.625 0 0 1 6.625 3");
}

</style>
