<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sawqznj2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:transfer-reverse" /></template>
<style>
.sawqznj2a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M20 6H7m3.5-3.5L7 6l3.5 3.5M4 12h13m-3.5-3.5L17 12l-3.5 3.5M21 18h-6m2.5-2.5L15 18l2.5 2.5");
}

</style>
