<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yc4ykbcsb"/><path class="e7oflvbej"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pores" /></template>
<style>
.e7oflvbej {
  d: path("M5.75 9a3 2.25 0 1 0 6 0a3 2.25 0 1 0-6 0m7 3.25a2.5 1.75 0 1 0 5 0a2.5 1.75 0 1 0-5 0m-5 4a2 1.5 0 1 0 4 0a2 1.5 0 1 0-4 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yc4ykbcsb {
  d: path("M12 2.5c6 0 9.5 3.5 9.5 9.5S18 21.5 12 21.5S2.5 18 2.5 12S6 2.5 12 2.5");
}

</style>
