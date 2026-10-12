<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cx6cowy4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:soup-kitchen-sharp" /></template>
<style>
.cx6cowy4u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 10.75h16l.804-.002l-.054.802A8.75 8.75 0 0 1 16 18.7v2.55H8V18.7a8.75 8.75 0 0 1-4.75-7.15l-.054-.802zm4.5-2.5l-1-1l1-1l1-1l-1-1m3.5 4l-1-1l1-1l1-1l-1-1m3.5 4l-1-1l1-1l1-1l-1-1");
}

</style>
