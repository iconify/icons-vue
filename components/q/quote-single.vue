<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uxj-_4pxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:quote-single" /></template>
<style>
.uxj-_4pxm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 4h6v7c0 5-2.5 8-7 9.5L8.5 19c2.5-1.25 3.75-3 4-5.5H10a2 2 0 0 1-2-2V6a2 2 0 0 1 2-2Z");
}

</style>
