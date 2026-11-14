<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rfr0v1bub"/><path class="wcrotzk2u"/><path class="e7h4og1sb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ozone-layer" /></template>
<style>
.e7h4og1sb {
  d: path("M13.5 11.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rfr0v1bub {
  d: path("M2.5 4q9.5-2 19 0m-19 13.75q9.5-2 19 0m-19 3.75q9.5-2 19 0m-16-10a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0");
}

.wcrotzk2u {
  d: path("M9.5 8.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0");
}

</style>
