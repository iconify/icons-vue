<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wkvspwlqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:storage-basket" /></template>
<style>
.wkvspwlqf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.171 8h13.658a1.75 1.75 0 0 1 1.71 2.122l-1.739 8a1.75 1.75 0 0 1-1.71 1.378H6.91a1.75 1.75 0 0 1-1.71-1.378l-1.739-8A1.75 1.75 0 0 1 5.171 8M5.5 8a2.5 2.5 0 0 1 5 0m3 0a2.5 2.5 0 0 1 5 0M4.25 13.75h15.5");
}

</style>
