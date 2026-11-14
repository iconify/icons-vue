<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ximkeuvzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:thistle" /></template>
<style>
.ximkeuvzw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 10.5c0 5 1.75 7 4.5 7s4.5-2 4.5-7Zm4.5 7v4m-3-11L6 4m6 6.5V3m3 7.5L18 4m-6 16c2-1.75 5-1.75 7-1c-2 2-5 2.25-7 1");
}

</style>
