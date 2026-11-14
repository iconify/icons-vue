<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="whc6b8bur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pin-tsunami" /></template>
<style>
.whc6b8bur {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 17.5c5 0 6.5-4.5 6.5-7.5c0-4 3-7 7-7C19.25 3 21 4.75 21 6.5c-3-1-5.5 1-5.5 4c0 4 3 7 5.5 7M3 21q3-1.5 6 0t6 0t6 0");
}

</style>
