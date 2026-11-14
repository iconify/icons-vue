<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="awws5--wg"/><path class="negtm6pnb"/><path class="ckqc5tb9v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:step-over" /></template>
<style>
.awws5--wg {
  d: path("M3 16a8 8 0 0 1 16 0");
}

.ckqc5tb9v {
  fill: currentColor;
  d: path("M8.5 18.75a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.negtm6pnb {
  d: path("M16.25 13.25L19 16l2.75-2.75");
}

</style>
