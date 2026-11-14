<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xn2gf6_ou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:simple-harmonic-motion" /></template>
<style>
.xn2gf6_ou {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 2.5h10m-5 0v2L12 6L6 8.5l6 2.5l-3 1v2.5m-3.5 0h7v7h-7Zm10.25-5.25L18 7l2.25 2.25M18 7v10m-2.25-2.25L18 17l2.25-2.25");
}

</style>
