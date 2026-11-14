<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uwvsv0rcx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:rash-guard" /></template>
<style>
.uwvsv0rcx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 3a3 2.5 0 0 0 6 0l4.5 2.5l2 13l-2.75.5l-2-9v11h-9.5V10l-2 9l-2.75-.5l2-13Zm.5 1.25L7.25 10m7.25-5.75L16.75 10");
}

</style>
