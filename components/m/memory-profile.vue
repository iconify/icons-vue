<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="eq45g_daq"/><path class="jov7ywodi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:memory-profile" /></template>
<style>
.eq45g_daq {
  d: path("M6 4h12a3.5 3.5 0 0 1 3.5 3.5v5A3.5 3.5 0 0 1 18 16H6a3.5 3.5 0 0 1-3.5-3.5v-5A3.5 3.5 0 0 1 6 4m0 12v3.5m4-3.5v3.5m4-3.5v3.5m4-3.5v3.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jov7ywodi {
  d: path("M5.5 13.25L9 9.5l3.5 1.5l6-4.25");
}

</style>
