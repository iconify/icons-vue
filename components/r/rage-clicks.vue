<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dihpxnbfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:rage-clicks" /></template>
<style>
.dihpxnbfy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.941 11.088l4.298 1.984a.832.832 0 0 1-.114 1.553l-1.313.386a1.5 1.5 0 0 0-1.027 1.057l-.41 1.557a.816.816 0 0 1-1.546.099l-1.907-4.711a1.5 1.5 0 0 1 2.019-1.925M9.5 2.5V6m-7 3.5H6m-3-6l1.75.5l-.5 1.25L6.5 6.5");
}

</style>
