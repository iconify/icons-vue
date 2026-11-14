<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hz5ryblgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sliders-vertical" /></template>
<style>
.hz5ryblgm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M18 3.5v9.25m0 4.5v3.25m-6-17v2.25m0 4.5V20.5m-6-17v7.25m0 4.5v5.25m9.75-5.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m-6-7a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m-6 5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0");
}

</style>
