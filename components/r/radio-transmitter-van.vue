<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zbbqtlbac"/><path class="pdm8yp7rn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:radio-transmitter-van" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pdm8yp7rn {
  d: path("M15 9.5V14h6.5M5 3.5a3.5 3.5 0 0 0 7 0ZM8.5 7v2.5m-3.5 9a2 2 0 1 0 4 0a2 2 0 1 0-4 0m10 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

.zbbqtlbac {
  d: path("M2.5 16.5V11A1.5 1.5 0 0 1 4 9.5h11l6.5 4.5v2.5Z");
}

</style>
