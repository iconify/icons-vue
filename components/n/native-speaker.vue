<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t4mm-gf5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:native-speaker" /></template>
<style>
.t4mm-gf5r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 7.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0ZM4 21c0-4 2.75-6 6.5-6s6.5 2 6.5 6m-.871-16.75a6.5 6.5 0 0 1 0 6.5M18.294 3a9 9 0 0 1 0 9");
}

</style>
