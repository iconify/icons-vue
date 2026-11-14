<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qwz6zrnei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mannequin-child" /></template>
<style>
.qwz6zrnei {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 7.5C7.75 7.5 7 8.75 7.25 10L8 12.5c-.5 1.25-.5 2.5.5 3.5h7c1-1 1-2.25.5-3.5l.75-2.5c.25-1.25-.5-2.5-2.25-2.5ZM10.75 5h2.5v2.5h-2.5ZM12 16v3.5m-4 2l4-2l4 2m-8-9h8");
}

</style>
