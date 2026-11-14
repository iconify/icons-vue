<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h9yvmub8g"/><path class="r10uzdh1b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:u-turn-up" /></template>
<style>
.h9yvmub8g {
  d: path("M4.5 3.5V14a5.5 5.5 0 0 0 11 0V3.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r10uzdh1b {
  d: path("m12 7l3.5-3.5L19 7");
}

</style>
