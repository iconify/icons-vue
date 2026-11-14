<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lomvmub0u"/><path class="jpeug_udb"/><path class="a2vftxo8q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:test-results-abnormal" /></template>
<style>
.a2vftxo8q {
  d: path("M19 3.5V10m-2.25-2.25L19 10l2.25-2.25m-7-4.25v3m0 2.5h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jpeug_udb {
  fill: currentColor;
  d: path("M9 13h4a1.5 1.5 0 0 1 1.5 1.5V16a1.5 1.5 0 0 1-1.5 1.5H9A1.5 1.5 0 0 1 7.5 16v-1.5A1.5 1.5 0 0 1 9 13");
}

.lomvmub0u {
  d: path("M4.75 13h14.5a2.25 2.25 0 0 1 2.25 2.25a2.25 2.25 0 0 1-2.25 2.25H4.75a2.25 2.25 0 0 1-2.25-2.25A2.25 2.25 0 0 1 4.75 13");
}

</style>
