<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="loiwzx-lp"/><path class="kdmwsxdku"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:spin-mop" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kdmwsxdku {
  d: path("M8.5 18.5q4-3 8 0");
}

.loiwzx-lp {
  d: path("m4 10.5l1.75 9.25a2 2 0 0 0 2 1.75h8.5a2 2 0 0 0 2-1.75L20 10.5m-17.5 0h19m-5.5-8l-3.5 14");
}

</style>
