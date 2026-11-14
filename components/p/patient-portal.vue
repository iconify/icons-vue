<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ew77xxbyo"/><path class="uk8f1acvc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:patient-portal" /></template>
<style>
.ew77xxbyo {
  d: path("M6 3.5h12A3.5 3.5 0 0 1 21.5 7v10a3.5 3.5 0 0 1-3.5 3.5H6A3.5 3.5 0 0 1 2.5 17V7A3.5 3.5 0 0 1 6 3.5m-3.5 4h19M5 5.5h.01m2.49 0h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uk8f1acvc {
  d: path("M7 12a1.75 1.75 0 1 0 3.5 0A1.75 1.75 0 1 0 7 12m-1 5.5C6 16 7.25 15 8.75 15s2.75 1 2.75 2.5M14 12h4.5M14 15.5h4.5");
}

</style>
