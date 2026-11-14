<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c91iy4b5g"/><path class="nbzhc4-cd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:van-insurance" /></template>
<style>
.c91iy4b5g {
  d: path("M2.5 16.5v-8a2 2 0 0 1 2-2H14l6 5l1.5 1v4ZM5.25 19a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m10 0a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nbzhc4-cd {
  d: path("m7.5 8.75l2.5 1v1.75c0 1.5-1 2.25-2.5 2.75C6 13.75 5 13 5 11.5V9.75Z");
}

</style>
