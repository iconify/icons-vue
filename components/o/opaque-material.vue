<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uz59bvw5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:opaque-material" /></template>
<style>
.uz59bvw5v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.5 3h7v18h-7Zm-12 5H11M8.75 5.75L11 8l-2.25 2.25M2.5 16H11m-2.25-2.25L11 16l-2.25 2.25");
}

</style>
