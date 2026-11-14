<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="suv9qbbmd"/><path class="e9seflbvn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:solenoid" /></template>
<style>
.e9seflbvn {
  d: path("M3.5 10.5c0-7 17-7 17 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.suv9qbbmd {
  d: path("M6 14.5a2 4 0 1 1 4 0a2 4 0 1 1-4 0m4 0a2 4 0 1 1 4 0a2 4 0 1 1-4 0m4 0a2 4 0 1 1 4 0a2 4 0 1 1-4 0m-11.5 0H6m12 0h3.5");
}

</style>
