<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sag7jf_2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:price-per-area" /></template>
<style>
.sag7jf_2w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 21L20 3m-5.5 11.5h7v7h-7ZM9 4.75c-.25-.5-1-1-2-1c-1.25 0-2 .75-2 1.75c0 2.25 4 1.5 4 4c0 1-.75 1.75-2 1.75s-2-.5-2.25-1.25M7 2.5v1.25m0 7.5v1.25");
}

</style>
