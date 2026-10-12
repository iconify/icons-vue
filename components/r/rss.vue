<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="sbe8-1cdf"/><path class="wft81v-mo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:rss" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sbe8-1cdf {
  cx: 5.5px;
  cy: 18.5px;
  r: 1.25px;
}

.wft81v-mo {
  d: path("M4.25 11.25a8.5 8.5 0 0 1 8.5 8.5m-8.5-15.5a15.5 15.5 0 0 1 15.5 15.5");
}

</style>
