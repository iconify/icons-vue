<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yv7c09fyu"/><path class="btc8kfbrr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pajamas" /></template>
<style>
.btc8kfbrr {
  d: path("M9.25 3.5L12 6.75l2.75-3.25M12 6.75v14M18.85 9a2.75 2.75 0 1 0 0 4.5a2.6 2.6 0 0 1 0-4.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yv7c09fyu {
  d: path("M9.75 3.25h4.5q1.25 0 2.35.58l2.05 1.09q1.1.58 1.23 1.82l1.24 12.02q.13 1.24-1.09 1.5l-1.06.23q-1.22.26-2.47.26h-9q-1.25 0-2.47-.26l-1.06-.23q-1.22-.26-1.09-1.5L4.12 6.74q.13-1.24 1.23-1.82L7.4 3.83q1.1-.58 2.35-.58");
}

</style>
