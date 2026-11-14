<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pbwepxb2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:zoom-fit" /></template>
<style>
.pbwepxb2b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 8.5h7v7h-7ZM2.5 7V2.5H7m-4.5 0L6 6m11-3.5h4.5V7m0-4.5L18 6M2.5 17v4.5H7m-4.5 0L6 18m11 3.5h4.5V17m0 4.5L18 18");
}

</style>
