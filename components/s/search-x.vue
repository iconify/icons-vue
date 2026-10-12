<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="ry59zbcad"/><path class="nedvnlz3b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:search-x" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nedvnlz3b {
  d: path("M7.75 11A3.25 3.25 0 0 1 11 7.75m5.5 8.75L21 21");
}

.ry59zbcad {
  cx: 11px;
  cy: 11px;
  r: 7.25px;
}

</style>
