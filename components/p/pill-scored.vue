<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ybpin5e7w"/><path class="x_qt-3bth"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pill-scored" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x_qt-3bth {
  d: path("M4 10.5v3a8 8 0 0 0 16 0v-3m-16 0h16");
}

.ybpin5e7w {
  d: path("M4 10.5a8 8 0 1 0 16 0a8 8 0 1 0-16 0");
}

</style>
