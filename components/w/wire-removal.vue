<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qkq-kybtx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:wire-removal" /></template>
<style>
.qkq-kybtx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.7 16.5H2.5v-14h16v7.2m-16 2.8l16-6m-4.889 12.061l4.95-4.95l2.828 2.828l-4.95 4.95Z");
}

</style>
