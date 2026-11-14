<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lmgrrfrdk"/><path class="r03jqjb-r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:suplex" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lmgrrfrdk {
  d: path("M5 19.5C5 1 19 1 19 16.5");
}

.r03jqjb-r {
  d: path("m16.5 14l2.5 2.5l2.5-2.5m-19 5.5h19");
}

</style>
