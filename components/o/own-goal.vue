<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hlta_2b8f"/><path class="mmw-4b41y"/><path class="ivqmgiboa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:own-goal" /></template>
<style>
.hlta_2b8f {
  d: path("M2.5 20V4h19v16");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ivqmgiboa {
  d: path("M6 20V7.5h12V20M2.5 4L6 7.5M21.5 4L18 7.5");
}

.mmw-4b41y {
  d: path("M9.25 14.5a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0");
}

</style>
