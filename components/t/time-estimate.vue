<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="me26nsb9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:time-estimate" /></template>
<style>
.me26nsb9d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 3h14M5 21h14M6.5 3v2.5C6.5 9 11 10.25 11 12s-4.5 3-4.5 6.5V21m11-18v2.5C17.5 9 13 10.25 13 12s4.5 3 4.5 6.5V21m-8 0l2.5-3l2.5 3");
}

</style>
