<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kzinkcs-l"/><path class="g4xwfub4x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:planetarium" /></template>
<style>
.g4xwfub4x {
  d: path("M12 10.25q.5 1.75 2.25 2.25q-1.75.5-2.25 2.25q-.5-1.75-2.25-2.25Q11.5 12 12 10.25m0-8v2.5m-7.25.5L6.5 7m12.75-1.75L17.5 7");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kzinkcs-l {
  d: path("M7 12.5a5 5 0 1 0 10 0a5 5 0 1 0-10 0M8.5 16L7 20.5m8.5-4.5l1.5 4.5");
}

</style>
