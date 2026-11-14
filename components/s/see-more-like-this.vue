<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w6upedbis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:see-more-like-this" /></template>
<style>
.w6upedbis {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 2.5h8v19H8ZM8 6H5a2 2 0 0 0-2 2v8a2 2 0 0 0 2 2h3m8-12h3a2 2 0 0 1 2 2v8a2 2 0 0 1-2 2h-3");
}

</style>
