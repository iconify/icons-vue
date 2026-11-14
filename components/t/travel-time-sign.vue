<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fsi1v-etm"/><path class="l62oq7bvv"/><path class="l_y5tz2gr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:travel-time-sign" /></template>
<style>
.fsi1v-etm {
  d: path("M6 3h12a3.5 3.5 0 0 1 3.5 3.5v6A3.5 3.5 0 0 1 18 16H6a3.5 3.5 0 0 1-3.5-3.5v-6A3.5 3.5 0 0 1 6 3m1 13v5m10-5v5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l_y5tz2gr {
  d: path("M8.25 8v1.5l1.25 1M14.25 8h4.5m-4.5 3h4.5");
}

.l62oq7bvv {
  d: path("M5.25 9.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

</style>
