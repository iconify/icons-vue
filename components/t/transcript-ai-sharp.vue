<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lrttepbfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:transcript-ai-sharp" /></template>
<style>
.lrttepbfb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 2.75h16.5v18.5H3.75zM7 7.5h1.5M7 12h1.5M7 16.5h1.5m2.5-9h6M11 12h6m-6 4.5h4");
}

</style>
