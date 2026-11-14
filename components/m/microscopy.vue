<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ubghjwb1d"/><path class="ljoa3-byl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:microscopy" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ljoa3-byl {
  d: path("M16.5 21c3.5-4 3-10-3.25-12.75M8.5 15.5h7");
}

.ubghjwb1d {
  d: path("m7.783 3.295l.434-.25a1.75 1.75 0 0 1 2.39.64l3.25 5.63a1.75 1.75 0 0 1-.64 2.39l-.434.25a1.75 1.75 0 0 1-2.39-.64l-3.25-5.63a1.75 1.75 0 0 1 .64-2.39M5 21h14");
}

</style>
