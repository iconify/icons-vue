<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="y6i3hfbkv"/><path class="zr2ew8c5u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:universal-remote" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y6i3hfbkv {
  d: path("M10.875 2.5h2.25A4.375 4.375 0 0 1 17.5 6.875v10.25a4.375 4.375 0 0 1-4.375 4.375h-2.25A4.375 4.375 0 0 1 6.5 17.125V6.875A4.375 4.375 0 0 1 10.875 2.5");
}

.zr2ew8c5u {
  d: path("M9.25 8.25a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0m.5 7.75h.01m4.49 0h.01");
}

</style>
