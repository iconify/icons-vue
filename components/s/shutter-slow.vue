<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r1gile42q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:shutter-slow" /></template>
<style>
.r1gile42q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 12a6.5 6.5 0 1 0 13 0a6.5 6.5 0 1 0-13 0ZM15 9.25l4.5 7.5m-2-3.25H8.75m3.75 0l4.25-7.75M3.5 8.5h2.75M2.5 12h3.25M3.5 15.5h2.75");
}

</style>
