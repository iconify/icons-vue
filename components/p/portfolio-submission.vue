<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zos_6foac"/><path class="hly-ncb_j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:portfolio-submission" /></template>
<style>
.hly-ncb_j {
  d: path("M5 10V8a1 1 0 0 1 1-1h10.5v11.5h-2m-12 .5l4-3.5l3 2.5m1.25-4.5h.01m8.49-.5V3M17 5.25L19.25 3l2.25 2.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zos_6foac {
  d: path("M5.125 10h6.75a2.625 2.625 0 0 1 2.625 2.625v6.25a2.625 2.625 0 0 1-2.625 2.625h-6.75A2.625 2.625 0 0 1 2.5 18.875v-6.25A2.625 2.625 0 0 1 5.125 10");
}

</style>
