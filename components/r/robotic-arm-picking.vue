<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vi0f-xafa"/><path class="p0reog-7q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:robotic-arm-picking" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p0reog-7q {
  d: path("M6.5 10a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0M18 9.5V13m-1.5 0h3");
}

.vi0f-xafa {
  d: path("M5.75 17h4.5A1.75 1.75 0 0 1 12 18.75a1.75 1.75 0 0 1-1.75 1.75h-4.5A1.75 1.75 0 0 1 4 18.75A1.75 1.75 0 0 1 5.75 17M8 17v-7l6-4m0 0l4 3.5");
}

</style>
