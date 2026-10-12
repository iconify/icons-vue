<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kog5qfbcn"/><path class="m2wgly_mi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:refund" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kog5qfbcn {
  d: path("M6.75 2.75h10.5a2 2 0 0 1 2 2v16.5l-2.4-1.5l-2.45 1.5l-2.4-1.5l-2.4 1.5l-2.45-1.5l-2.4 1.5V4.75a2 2 0 0 1 2-2");
}

.m2wgly_mi {
  d: path("m10.75 7.25l-2 2l2 2m-2-2h4.5a2.25 2.25 0 0 1 0 4.5h-1.5");
}

</style>
