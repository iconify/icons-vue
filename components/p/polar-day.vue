<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mhfzlwu4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:polar-day" /></template>
<style>
.mhfzlwu4q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 11a4 4 0 1 0 8 0a4 4 0 1 0-8 0m4-6.5v-2m4.5 4L18 5m.5 6h2m-4 4.5L18 17M7.5 15.5L6 17m-.5-6h-2m4-4.5L6 5M2.5 20.5h19");
}

</style>
