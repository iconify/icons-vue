<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uetd-nbvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:race-spotter" /></template>
<style>
.uetd-nbvi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 8.5h6v7h-6Zm9 0h6v7h-6Zm-3 3.5h3M8 8.5a4.25 4.25 0 1 1 8 0m-12 13c0-2 3.5-3.25 8-3.25s8 1.25 8 3.25");
}

</style>
