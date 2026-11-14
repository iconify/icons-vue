<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e8wwqrbgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:spring-scale" /></template>
<style>
.e8wwqrbgc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 5.5h7v11h-7Zm3.5-3v3M8.5 9h2m-2 3.5h2m1-1.75h4M12 16.5v2a1.75 1.75 0 1 1-1.75 1.75");
}

</style>
