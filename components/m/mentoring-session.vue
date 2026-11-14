<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="il3f5ubai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mentoring-session" /></template>
<style>
.il3f5ubai {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 7.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0ZM4 21c0-4 3.5-6.5 8-6.5q.179 0 .356.005M16.5 21.5v-1.75c-1-.75-1.75-1.75-1.75-3a3.25 3.25 0 0 1 6.5 0c0 1.25-.75 2.25-1.75 3v1.75Z");
}

</style>
