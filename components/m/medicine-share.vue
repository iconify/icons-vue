<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="unvz5bc3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:medicine-share" /></template>
<style>
.unvz5bc3w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 5za3 3 0 0 1 3 3v8a3 3 0 0 1-3 3a3 3 0 0 1-3-3V8a3 3 0 0 1 3-3m-3 7h6m5.75-6a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0m0 12a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0M9.5 9.5l6-2.5m-6 7.5l6 2.5");
}

</style>
