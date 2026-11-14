<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x17du5wii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:stickiness" /></template>
<style>
.x17du5wii {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.872 21H4.5c-.6 0-1-.4-1-1c0-3.25 3.25-5.5 7.5-5.5q.225 0 .445.008M7 7.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm8 7v3.75a3 3 0 0 0 6 0V14.5m-6.75 1.75h1.5m4.5 0h1.5");
}

</style>
