<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="msu-j7v-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:teeth" /></template>
<style>
.msu-j7v-w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.25 9c0-2 1-3 2-2.5q.75.375 1.5 0c1-.5 2 .5 2 2.5s-.5 3.5-.75 5l-.25 3.5c-.25 1-1 1-1.25 0l-.5-2l-.5 2c-.25 1-1 1-1.25 0L3 14c-.25-1.5-.75-3-.75-5Zm7 0c0-2 1-3 2-2.5q.75.375 1.5 0c1-.5 2 .5 2 2.5s-.5 3.5-.75 5l-.25 3.5c-.25 1-1 1-1.25 0l-.5-2l-.5 2c-.25 1-1 1-1.25 0L10 14c-.25-1.5-.75-3-.75-5Zm7 0c0-2 1-3 2-2.5q.75.375 1.5 0c1-.5 2 .5 2 2.5s-.5 3.5-.75 5l-.25 3.5c-.25 1-1 1-1.25 0l-.5-2l-.5 2c-.25 1-1 1-1.25 0L17 14c-.25-1.5-.75-3-.75-5Z");
}

</style>
