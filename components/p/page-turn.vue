<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nk9qdqb0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:page-turn" /></template>
<style>
.nk9qdqb0c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.7 20H3.5V2.5H18v10.1M7 7.5h7.5m-7.5 4h5m9.5 7h-7m2.75-2.75L14.5 18.5l2.75 2.75");
}

</style>
