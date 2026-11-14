<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i8_e1b2ka"/><path class="raiwcmtvc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:watering-bottom" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i8_e1b2ka {
  d: path("M8.048 8h7.904a1.75 1.75 0 0 1 1.729 2.023l-.948 6a1.75 1.75 0 0 1-1.728 1.477h-6.01a1.75 1.75 0 0 1-1.728-1.477l-.948-6A1.75 1.75 0 0 1 8.048 8M3 17.5h18l-1.5 3h-15Zm9-2.75V11");
}

.raiwcmtvc {
  d: path("M9.75 13.25L12 11l2.25 2.25M12 8V5.5c0-2 1.75-3 4-3c0 2-1.75 3-4 3");
}

</style>
