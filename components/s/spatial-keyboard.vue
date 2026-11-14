<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mk5pgw-1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:spatial-keyboard" /></template>
<style>
.mk5pgw-1n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 6h16l-3 12h-16Zm2 4H9m2.75 0h1.5M16 10h1.5m-11 4H8m2.75 0h1.5M15 14h1.5");
}

</style>
