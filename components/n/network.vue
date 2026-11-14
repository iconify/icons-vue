<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tqyxpqbnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:network" /></template>
<style>
.tqyxpqbnl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 12.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm.5-8a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm-7.5 14a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm15 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM12 6.5V10m-5.75 7.25l3.75-3m7.75 3l-3.75-3");
}

</style>
