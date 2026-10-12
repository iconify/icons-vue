<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lsi4qfbfx"/><rect class="aidaq1nyl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:medical-glove" /></template>
<style>
.aidaq1nyl {
  width: 12.5px;
  height: 6px;
  x: 5.25px;
  y: 15.25px;
  rx: 1.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lsi4qfbfx {
  d: path("M6.25 15.25V8a1.25 1.25 0 0 1 2.5 0V4.75a1.25 1.25 0 0 1 2.5 0v-.5a1.25 1.25 0 0 1 2.5 0v1a1.25 1.25 0 0 1 2.5 0v7.25l1.6-1.6a1.4 1.4 0 0 1 2 2l-2.6 2.35Zm2.5-6.75V12m2.5-7v7m2.5-6.5V12");
}

</style>
