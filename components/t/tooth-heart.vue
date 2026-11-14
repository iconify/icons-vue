<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h98u8yx3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tooth-heart" /></template>
<style>
.h98u8yx3w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M19.033 12.502C19.502 11.031 20 9.765 20 8c0-2.5-1-4.5-3.5-4.5c-2 0-3 1-4.5 1s-2.5-1-4.5-1C5 3.5 4 5.5 4 8s1 4 1.5 6.5l1 5c.25 1.25 1.75 1.25 2 0l1-4.5c.25-1 1.25-1.5 2.5-1.5c.414 0 .801.055 1.142.165M18 21.5l-2.75-2.75c-1-1-.75-3.5 1-3.5c1 0 1.5.75 1.75 1.25c.25-.5.75-1.25 1.75-1.25c1.75 0 2 2.5 1 3.5Z");
}

</style>
