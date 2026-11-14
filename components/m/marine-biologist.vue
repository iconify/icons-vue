<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nqiqnkytx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:marine-biologist" /></template>
<style>
.nqiqnkytx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.672 20.5H4c-.6 0-1-.4-1-1c0-3.25 3.25-5.5 7.5-5.5c.966 0 1.881.116 2.717.334M6.5 7a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm8.5 9.5q1.625-1.5 3.25 0t3.25 0M15 20q1.625-1.5 3.25 0t3.25 0");
}

</style>
