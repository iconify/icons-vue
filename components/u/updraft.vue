<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nkftt-72u"/><path class="ot94gkbbl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:updraft" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nkftt-72u {
  d: path("M12 21.5c-1.25-3 1.25-6 0-9V3");
}

.ot94gkbbl {
  d: path("M6.5 8.5L12 3l5.5 5.5M7 21.5c-1.25-3 1.25-6 0-9m10 9c-1.25-3 1.25-6 0-9");
}

</style>
