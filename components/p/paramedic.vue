<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uq-ej-pgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:paramedic" /></template>
<style>
.uq-ej-pgs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.272 20.5H4c-.6 0-1-.4-1-1c0-3.25 3.25-5.5 7.5-5.5q.651 0 1.267.069M6.5 7a4 4 0 1 0 8 0a4 4 0 1 0-8 0m10 6.5H19v2l1.75-1L22 16.75l-1.75 1l1.75 1L20.75 21L19 20v2h-2.5v-2l-1.75 1l-1.25-2.25l1.75-1l-1.75-1l1.25-2.25l1.75 1Zm1.25 2.25v4");
}

</style>
