<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t5ekwh3zc"/><path class="m_oal9ugc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sort-numeric-up" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m_oal9ugc {
  d: path("M19 15.75v2.75a2 2 0 0 1-2 2h-1.5");
}

.t5ekwh3zc {
  d: path("M6.5 20V4m-3 3l3-3l3 3m5.25-1.75l2-1.75v7m-2.25 5.25a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0");
}

</style>
