<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bwu5yfbxr"/><path class="dxli9rluy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:whirlpool" /></template>
<style>
.bwu5yfbxr {
  d: path("M14.5 12a2.5 2.5 0 0 0-5 0a4.5 4.5 0 0 0 9 0A7.25 7.25 0 0 0 4 12");
}

.dxli9rluy {
  d: path("M7.5 20A9 9 0 0 0 21 12");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
