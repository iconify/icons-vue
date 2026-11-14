<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qb2z38ble"/><path class="qg8v3cbks"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:park-and-ride" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qb2z38ble {
  d: path("M6.875 2.5h3.25A4.375 4.375 0 0 1 14.5 6.875v6.25a4.375 4.375 0 0 1-4.375 4.375h-3.25A4.375 4.375 0 0 1 2.5 13.125v-6.25A4.375 4.375 0 0 1 6.875 2.5M5.5 17.5V20m6-2.5V20");
}

.qg8v3cbks {
  d: path("M7 5.25h3A1.75 1.75 0 0 1 11.75 7v1.5A1.75 1.75 0 0 1 10 10.25H7A1.75 1.75 0 0 1 5.25 8.5V7A1.75 1.75 0 0 1 7 5.25M5.75 14h.01m5.49 0h.01m6.24 7.75V15h2a2.25 2.25 0 0 1 0 4.5h-2");
}

</style>
