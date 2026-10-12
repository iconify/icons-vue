<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fnf6tacsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sledgehammer-sharp" /></template>
<style>
.fnf6tacsx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.4 3.81l7.79 7.79l1.06 1.06l-1.06 1.06l-2.32 2.32l-1.06 1.06l-1.06-1.06l-7.79-7.79L6.9 7.19l1.06-1.06l2.32-2.32l1.06-1.06zm1.5 1.5L9.46 9.76m9.23.34l-4.45 4.44m-3.41-1.37l-7.35 7.35");
}

</style>
