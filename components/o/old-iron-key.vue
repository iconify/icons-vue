<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h-q-0xbtd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:old-iron-key" /></template>
<style>
.h-q-0xbtd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6 8l4 4l-4 4l-4-4Zm4 4h11m-8.5-2v4m4.5-2v3.5h1.5V14H20v1.5h1V12");
}

</style>
