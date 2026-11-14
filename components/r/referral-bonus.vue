<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gxbma6bql"/><path class="sbs647idy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:referral-bonus" /></template>
<style>
.gxbma6bql {
  d: path("M5.75 15h4.5A2.75 2.75 0 0 1 13 17.75a2.75 2.75 0 0 1-2.75 2.75h-4.5A2.75 2.75 0 0 1 3 17.75A2.75 2.75 0 0 1 5.75 15");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sbs647idy {
  d: path("M13.75 15h4.5A2.75 2.75 0 0 1 21 17.75a2.75 2.75 0 0 1-2.75 2.75h-4.5A2.75 2.75 0 0 1 11 17.75A2.75 2.75 0 0 1 13.75 15m-.5-8.5a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0m3.25-1v2m-9-3h3M6.5 8H10");
}

</style>
