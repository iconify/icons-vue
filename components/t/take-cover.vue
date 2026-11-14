<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nvksyj4sm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:take-cover" /></template>
<style>
.nvksyj4sm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 7L5 4h14l2.5 3ZM5 7v14M19 7v14M6.75 13a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm.75 8c.5-2.25 2.5-3.5 5-3.5s4 1.5 4 3.5");
}

</style>
