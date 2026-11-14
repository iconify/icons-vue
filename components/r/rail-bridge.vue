<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cr-0_33vc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:rail-bridge" /></template>
<style>
.cr-0_33vc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2 4h20M3 20.5v-8.75h18v8.75M7 11.75v8.75m10-8.75v8.75M3 11.75L7.5 4l4.5 7.75L16.5 4l4.5 7.75");
}

</style>
