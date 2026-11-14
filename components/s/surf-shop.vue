<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n265mlbsz"/><path class="cs72wobds"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:surf-shop" /></template>
<style>
.cs72wobds {
  d: path("M19.5 2.5v19H4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n265mlbsz {
  d: path("M8.5 12.5a3.5 9.5 0 1 0 7 0a3.5 9.5 0 1 0-7 0m5.552-5.638L9.948 18.138");
}

</style>
