<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rlbthab0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:noise-level" /></template>
<style>
.rlbthab0x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 10h4L13 5.5v13L7.5 14h-4ZM16 9.5c1.5 1.5 1.5 3.5 0 5M18.5 7c2.5 2.5 2.5 7.5 0 10");
}

</style>
