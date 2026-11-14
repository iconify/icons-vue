<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i4dk2hkfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:screw" /></template>
<style>
.i4dk2hkfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.975 3h6.05a1.025 1.025 0 0 1 .725 1.75l-1.311 1.311a1.5 1.5 0 0 1-1.06.439h-2.758a1.5 1.5 0 0 1-1.06-.439L8.25 4.75A1.025 1.025 0 0 1 8.975 3M11.5 6.5h1A1.5 1.5 0 0 1 14 8v7.682a1.5 1.5 0 0 1-.129.609L13 18.25a1.094 1.094 0 0 1-2 0l-.871-1.959a1.5 1.5 0 0 1-.129-.609V8a1.5 1.5 0 0 1 1.5-1.5M10 10l4-1m-4 4.5l4-1");
}

</style>
