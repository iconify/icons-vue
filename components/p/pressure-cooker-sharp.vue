<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nlaa8pbrj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pressure-cooker-sharp" /></template>
<style>
.nlaa8pbrj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 2.75H11v3.5H8.5zM3 9.5c0-2 3-3.25 6.75-3.25S16.5 7.5 16.5 9.5Zm13.5-1h4.75m-4.75 5h4.75M3 12h13.5v9.25H3zm0 2.5h13.5");
}

</style>
