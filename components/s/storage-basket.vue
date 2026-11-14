<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g31kwac0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:storage-basket" /></template>
<style>
.g31kwac0x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 8h18l-2.5 11.5h-13Zm2.5 0a2.5 2.5 0 0 1 5 0m3 0a2.5 2.5 0 0 1 5 0M4.25 13.75h15.5");
}

</style>
