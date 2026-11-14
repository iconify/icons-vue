<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="y0t0_4uif"/><path class="a6k62accz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:send-clock" /></template>
<style>
.a6k62accz {
  d: path("M18 16.5V18l1.25 1");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y0t0_4uif {
  d: path("m5.595 6.962l6.114-2.445a1.75 1.75 0 0 1 2.274 2.274l-2.445 6.114A1.255 1.255 0 0 1 9.25 13l-.989-1.978a1.75 1.75 0 0 0-.783-.783L5.5 9.25a1.255 1.255 0 0 1 .095-2.288M8 10.5L15.5 3m-.75 15a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0");
}

</style>
