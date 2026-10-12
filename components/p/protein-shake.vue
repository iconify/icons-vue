<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v6s6iinaq"/><circle class="rqfaqacav"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:protein-shake" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rqfaqacav {
  cx: 12px;
  cy: 16.125px;
  r: 2px;
}

.v6s6iinaq {
  d: path("M5.5 8a6.5 3.25 0 0 1 13 0Zm8.25-3.15L15 3m-6.75 8h7.5q1.75 0 1.58 1.74l-.66 6.77q-.17 1.74-1.92 1.74h-5.5q-1.75 0-1.92-1.74l-.66-6.77Q6.5 11 8.25 11");
}

</style>
