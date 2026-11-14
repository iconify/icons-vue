<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ulcolbbfz"/><path class="ceoj2obcg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:meditation-music" /></template>
<style>
.ceoj2obcg {
  d: path("M11 13.5c-5 0-8-2.5-8.5-6c2.5 0 4.75 1 6 2.5m2.5 3.5c5 0 8-2.5 8.5-6c-2.5 0-4.75 1-6 2.5m5.5 4.5v5m-3.5 0a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m3.5-5l2.5 1");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ulcolbbfz {
  d: path("M11 3c3 2.5 3 7 0 10.5C8 10 8 5.5 11 3");
}

</style>
