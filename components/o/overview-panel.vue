<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="clo8k5olx"/><path class="ebv8mxxvw"/><path class="wmth3xbmo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:overview-panel" /></template>
<style>
.clo8k5olx {
  d: path("M6.375 3h11.25A4.375 4.375 0 0 1 22 7.375v9.25A4.375 4.375 0 0 1 17.625 21H6.375A4.375 4.375 0 0 1 2 16.625v-9.25A4.375 4.375 0 0 1 6.375 3M2 8h20M4.75 5.5H9.5M8.75 8v13m6.5-13v13M4.5 17.5v-3m2.25 3V12");
}

.ebv8mxxvw {
  fill: currentColor;
  d: path("M12 13.75zA1.25 1.25 0 0 1 13.25 15A1.25 1.25 0 0 1 12 16.25A1.25 1.25 0 0 1 10.75 15A1.25 1.25 0 0 1 12 13.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wmth3xbmo {
  d: path("m17 17l1.25-3l1.5 1.25l.5-2.75");
}

</style>
