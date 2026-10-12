<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="rzyzgqcqn"/><path class="lqmqmxptf"/><circle class="nvay6mg0g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:orbit-path-sharp" /></template>
<style>
.lqmqmxptf {
  d: path("M19.58 9.13a9.25 5 0 1 1-6.77-2.11");
}

.nvay6mg0g {
  cx: 16.63px;
  cy: 7.67px;
  r: 2px;
}

.rzyzgqcqn {
  cx: 12px;
  cy: 12px;
  r: 2.25px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
