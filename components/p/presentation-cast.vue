<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uepnzcbdk"/><path class="bq42kvbax"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:presentation-cast" /></template>
<style>
.bq42kvbax {
  d: path("M13.5 2.25a8.25 8.25 0 0 1 8.25 8.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uepnzcbdk {
  d: path("M6 10.5h4a3.5 3.5 0 0 1 3.5 3.5v1a3.5 3.5 0 0 1-3.5 3.5H6A3.5 3.5 0 0 1 2.5 15v-1A3.5 3.5 0 0 1 6 10.5m2 8v3m-3 0h6m2.5-13.75a2.75 2.75 0 0 1 2.75 2.75M13.5 5a5.5 5.5 0 0 1 5.5 5.5");
}

</style>
