<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="axv8cvb1u"/><path class="fi4_6lbjh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:radio-antenna-telescopic" /></template>
<style>
.axv8cvb1u {
  d: path("M6 9h12a3.5 3.5 0 0 1 3.5 3.5V17a3.5 3.5 0 0 1-3.5 3.5H6A3.5 3.5 0 0 1 2.5 17v-4.5A3.5 3.5 0 0 1 6 9m9.5 0L20 3");
}

.fi4_6lbjh {
  d: path("M5.25 14.75a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0M13.5 13h5m-5 3.5h5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
