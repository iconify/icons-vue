<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hku6f6eqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:split-bill" /></template>
<style>
.hku6f6eqj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 2.5h7V21l-1.75-1.25L6.5 21l-1.75-1.25L3 21Zm11 0h7V21l-1.75-1.25L17.5 21l-1.75-1.25L14 21Zm-8.5 5h2m9 0h2");
}

</style>
