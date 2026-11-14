<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p_wh_ebtx"/><path class="t_e8cdpmr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:neutrino-detector" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p_wh_ebtx {
  d: path("M6.5 5a5.5 2 0 1 0 11 0a5.5 2 0 1 0-11 0");
}

.t_e8cdpmr {
  d: path("M6.5 5v14a5.5 2 0 0 0 11 0V5M3 17.5l1.5-1m4.5-3l6-4m4.5-3l1.5-1");
}

</style>
