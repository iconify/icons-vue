<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jt2tn6g0v"/><path class="ead9-3b2g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:overgrown-hedge" /></template>
<style>
.ead9-3b2g {
  d: path("M7 10.5q.5-4.5-4-5q-.5 4.5 4 5m10 0q-.5-5.5 4-7q1 5.5-4 7M12 9V5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jt2tn6g0v {
  d: path("M3 20v-6c0-2.5 2-4 4-3.5c1-2 3.5-2.5 5-1.5c1.5-1 4-.5 5 1.5c2-.5 4 1 4 3.5v6Z");
}

</style>
