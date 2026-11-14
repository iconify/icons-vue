<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ly--h0hjp"/><path class="djo210zfi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:test-pending" /></template>
<style>
.djo210zfi {
  fill: currentColor;
  d: path("M17.652 21.25h.696a.53.53 0 0 0 .402-.875a.988.988 0 0 0-1.5 0a.53.53 0 0 0 .402.875");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ly--h0hjp {
  d: path("M6.5 3v11c0 2 1.5 3.5 3.5 3.5c1.231 0 2.273-.568 2.892-1.472m.608-4.158V3M5 3h10m-8.5 7h7m1.5 4.25h6m-6 7.5h6m-5.25-7.5l4.5 7.5m0-7.5l-4.5 7.5");
}

</style>
