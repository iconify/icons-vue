<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f48mfb8re"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:title-search" /></template>
<style>
.f48mfb8re {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 2.5h15V6h-15ZM6 6v12M18 6v6m-3.9 9.5H4.5V18H12m-3-8h6m-6 3.5h4m1.75 3.75a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0ZM19 19l2.5 2.5");
}

</style>
