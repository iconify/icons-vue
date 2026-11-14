<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ixsjsr_0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:temperature-low-alert" /></template>
<style>
.ixsjsr_0r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.25 13V4.5a2.25 2.25 0 0 1 4.5 0V13a4.5 4.5 0 1 1-4.5 0Zm2.25 4h.01M18 14.75v3.5M18 21h.01");
}

</style>
