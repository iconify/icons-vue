<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u-9rv_xyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:signal-crossing" /></template>
<style>
.u-9rv_xyf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 4.25a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0M7 8.5l-1.25 4.25L3.25 17m2.5-4.25L8.5 17m-4.75-6.5L7 8.5l2.25 2.25m7.875-8.25h1.75A2.625 2.625 0 0 1 21.5 5.125v4.25A2.625 2.625 0 0 1 18.875 12h-1.75A2.625 2.625 0 0 1 14.5 9.375v-4.25A2.625 2.625 0 0 1 17.125 2.5M18 12v9.5m0-16h.01M2.5 20.5H6m3 0h3.5");
}

</style>
