<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a5x66xb4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:patient-list" /></template>
<style>
.a5x66xb4u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 5h11.5M10 12h11.5M10 19h11.5M3.25 4a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0ZM2.5 8c0-1.25 1-1.75 2.25-1.75S7 6.75 7 8m-3.75 3a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm-.75 4c0-1.25 1-1.75 2.25-1.75S7 13.75 7 15m-3.75 3a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm-.75 4c0-1.25 1-1.75 2.25-1.75S7 20.75 7 22");
}

</style>
