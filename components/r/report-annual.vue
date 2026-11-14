<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="recoc8jpg"/><path class="jwuqt6u1b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:report-annual" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jwuqt6u1b {
  d: path("M4.5 19.5v-15a2 2 0 0 1 2-2m-2 17v-1m6-4.5v-2.5m2.75 2.5V7.5M16 14V9.5");
}

.recoc8jpg {
  d: path("M6.5 2.5h13v15h-13a2 2 0 0 0 0 4h13");
}

</style>
