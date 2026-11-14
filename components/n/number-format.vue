<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rdsftubpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:number-format" /></template>
<style>
.rdsftubpa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.5 10l2-2v8m3-6a2 2 0 0 1 4 0c0 2.5-4 3.75-4 6h4m3-8H20l-2.25 3.5a2.25 2.25 0 1 1-1.5 3.25");
}

</style>
