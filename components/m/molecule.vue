<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ty65nfb_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:molecule" /></template>
<style>
.ty65nfb_b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 16a3 3 0 1 0 6 0a3 3 0 1 0-6 0ZM9 8a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm6.5 8a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm-8-2.5l2.5-3m4 0l2.5 3");
}

</style>
