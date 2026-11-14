<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lw2bgj63r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:simple-harmonic-motion" /></template>
<style>
.lw2bgj63r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 2.5h10m-5 0v2L12 6L6 8.5l6 2.5l-3 1v2.5m-.875 0h1.75a2.625 2.625 0 0 1 2.625 2.625v1.75A2.625 2.625 0 0 1 9.875 21.5h-1.75A2.625 2.625 0 0 1 5.5 18.875v-1.75A2.625 2.625 0 0 1 8.125 14.5m7.625-5.25L18 7l2.25 2.25M18 7v10m-2.25-2.25L18 17l2.25-2.25");
}

</style>
