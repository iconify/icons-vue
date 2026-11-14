<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fy_jccfhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:thermal-expansion" /></template>
<style>
.fy_jccfhc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 10h16v4H4Zm6-7c-1 1.5 1 2.5 0 4m4-4c-1 1.5 1 2.5 0 4M2.5 19h19M4.75 16.75L2.5 19l2.25 2.25m14.5-4.5L21.5 19l-2.25 2.25");
}

</style>
