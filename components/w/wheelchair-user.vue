<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="olg4f6bbi"/><path class="ard1fccgb"/><path class="a7-6__szj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:wheelchair-user" /></template>
<style>
.a7-6__szj {
  d: path("M8.38 11.33a5 5 0 1 0 5.79 4.05");
}

.ard1fccgb {
  d: path("M10.5 8.5v4.75h5.25l2 5.25h2.5m-9.75-8.25h4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.olg4f6bbi {
  cx: 11px;
  cy: 4.5px;
  r: 1.75px;
}

</style>
