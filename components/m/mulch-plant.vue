<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m1ab8s7ec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mulch-plant" /></template>
<style>
.m1ab8s7ec {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 19a8.5 2.5 0 1 0 17 0a8.5 2.5 0 1 0-17 0Zm8.5-2.5V4m0 6c0-4 3-6 7-6c0 4-3 6-7 6Zm0 3.5c0-3-2.5-5-6.5-5c0 3.5 2.5 5 6.5 5Z");
}

</style>
