<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qu7jzybes"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:planter-street" /></template>
<style>
.qu7jzybes {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.778 11h8.444a1.75 1.75 0 0 1 1.691 2.201l-1.067 4a1.75 1.75 0 0 1-1.69 1.299H7.844a1.75 1.75 0 0 1-1.69-1.299l-1.067-4A1.75 1.75 0 0 1 6.778 11M2.5 18.5H18v3h3.5M11 11V7m0 2.5c-3 0-5.5-2-5.5-5c3 0 5.5 2 5.5 5M11 7c0-2.5 2.5-4.5 5.5-4.5C16.5 5 14 7 11 7");
}

</style>
