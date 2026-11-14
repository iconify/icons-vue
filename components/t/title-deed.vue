<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qxlf-mbgr"/><path class="ma64ocbyo"/><path class="njz4xqbsa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:title-deed" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ma64ocbyo {
  fill: currentColor;
  d: path("M9.75 16.75a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0");
}

.njz4xqbsa {
  d: path("m11 18.75l-1 2.75m3-2.75l1 2.75");
}

.qxlf-mbgr {
  d: path("M5 14V5a1.75 1.75 0 0 0-1.75 1.75A1.75 1.75 0 0 0 5 8.5M19 5v9a1.75 1.75 0 0 0 1.75-1.75A1.75 1.75 0 0 0 19 10.5M5 5h14M5 14h14M8 8.25h8M8 11h5");
}

</style>
