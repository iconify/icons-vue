<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m54-wsbcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:shell-sharp" /></template>
<style>
.m54-wsbcp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 18.5c-4-1.25-7-4.75-7-8.25c0-4.25 4-7.5 9-7.5s9 3.25 9 7.5c0 3.5-3 7-7 8.25Zm-1.25 0h6.5v2.75h-6.5zM12 16.25V6M9.5 16L7 7.5m7.5 8.5L17 7.5");
}

</style>
