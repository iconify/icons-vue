<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b28ohdctn"/><path class="ksdbrpuig"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:soccer-chip" /></template>
<style>
.b28ohdctn {
  d: path("M6.5 8a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ksdbrpuig {
  d: path("m12.921 6.216l.54.42a1.5 1.5 0 0 1 .526 1.579l-.186.68A1.5 1.5 0 0 1 12.354 10h-.708a1.5 1.5 0 0 1-1.447-1.105l-.186-.68a1.5 1.5 0 0 1 .526-1.579l.54-.42a1.5 1.5 0 0 1 1.842 0M12 5.5v-3m2.25 4.75l3-1M13.5 10l1.75 2.5M10.5 10l-1.75 2.5m1-5.25l-3-1m-2 6.25q-1 3-1.25 8m15.75-8q1 3 1.25 8m-1.75-1.75l1.75 1.75l1.25-2");
}

</style>
