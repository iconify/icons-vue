<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wby573kfx"/><path class="w8slgyb0d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:utility-van" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w8slgyb0d {
  d: path("M4.5 17a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm10 0a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm-2-8.5h1.75l2.25 2.75h-4Z");
}

.wby573kfx {
  d: path("M4.5 16.5h-2V7A1.5 1.5 0 0 1 4 5.5h11.5l4 5h.5a1.5 1.5 0 0 1 1.5 1.5v4.5h-2m-10 0h5");
}

</style>
