<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aui3_6b0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:site-transformer" /></template>
<style>
.aui3_6b0x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14 21H2.5V8.5h16V11M7 8.5V4M5 4h4m5 4.5V4m-2 0h4m4 9.5L16 18h4l-3.25 4");
}

</style>
