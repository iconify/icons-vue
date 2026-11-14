<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gutm8acqz"/><path class="h4_m2nb8f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:okr" /></template>
<style>
.gutm8acqz {
  d: path("M2.5 12a5 5 0 1 0 10 0a5 5 0 1 0-10 0");
}

.h4_m2nb8f {
  d: path("M5.5 12a2 2 0 1 0 4 0a2 2 0 1 0-4 0m10-5h6m-6 5h4m-4 5H18");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
