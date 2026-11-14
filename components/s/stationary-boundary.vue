<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pbsy3bb7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:stationary-boundary" /></template>
<style>
.pbsy3bb7h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 16a9.5 4.5 0 1 0 19 0a9.5 4.5 0 1 0-19 0Zm6-12h7v3.5h-7Zm1 3.5v8m5-8v8");
}

</style>
