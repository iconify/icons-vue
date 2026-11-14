<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ijq7_cbts"/><path class="yxtt9bcmf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:targeted-therapy" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ijq7_cbts {
  d: path("M3.5 12a8.5 8.5 0 1 0 17 0a8.5 8.5 0 1 0-17 0");
}

.yxtt9bcmf {
  d: path("M12 7.5C13.25 7 14 8 14 9c1-.5 2 .5 1.75 1.5C17 11 17 12.75 16 13.25c.25 1.25-.75 2.25-2 2c-.5 1.25-2 1.75-2.75.75c-1 .5-2.5 0-2.25-1.25c-1.5-.25-2-1.75-1-2.5c-.75-1 0-2.5 1-2.5c0-1.25 1.5-2 2.5-1.5c0-.5 0-.75.5-.75m0-5v3m0 13v3M2.5 12h3m13 0h3");
}

</style>
