<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xhbqrmajq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pin-park-and-ride" /></template>
<style>
.xhbqrmajq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.5 3.5h4A3.5 3.5 0 0 1 21 7v8.5a3.5 3.5 0 0 1-3.5 3.5h-4a3.5 3.5 0 0 1-3.5-3.5V7a3.5 3.5 0 0 1 3.5-3.5M10 11h11m-8.5 8v2.5m6-2.5v2.5M2.5 6A2.25 2.25 0 1 0 7 6a2.25 2.25 0 1 0-4.5 0m2.25 2.25V21.5");
}

</style>
