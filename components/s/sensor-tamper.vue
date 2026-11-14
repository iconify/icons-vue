<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nihbf2-2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sensor-tamper" /></template>
<style>
.nihbf2-2l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 9A5.25 5.25 0 1 0 13 9A5.25 5.25 0 1 0 2.5 9Zm13.75-1.75a2.25 4.75 0 1 0 4.5 0a2.25 4.75 0 1 0-4.5 0ZM7.75 9h.01M18 14.75v3.5M18 21h.01");
}

</style>
