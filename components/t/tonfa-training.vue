<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m4vx_abzs"/><path class="bv1xbqbbj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tonfa-training" /></template>
<style>
.bv1xbqbbj {
  d: path("M9.525 16.95za1.5 1.5 0 0 1 2.121 0l1.768 1.768a1.5 1.5 0 0 1 0 2.121a1.5 1.5 0 0 1-2.121 0l-1.768-1.768a1.5 1.5 0 0 1 0-2.121");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m4vx_abzs {
  d: path("M5.282 16.243L16.243 5.282a1.75 1.75 0 0 1 2.475 0a1.75 1.75 0 0 1 0 2.475L7.757 18.718a1.75 1.75 0 0 1-2.475 0a1.75 1.75 0 0 1 0-2.475");
}

</style>
