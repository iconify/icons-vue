<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ozz_fjb0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:vent-closed" /></template>
<style>
.ozz_fjb0v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.9 3H21v14.1M17.1 21H3V6.9m9.4 1.6H17M7 12h1.1m7.8 0H17M7 15.5h4.6m-8.1-12l17 17");
}

</style>
