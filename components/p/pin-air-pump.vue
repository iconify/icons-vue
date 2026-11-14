<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="akntkhbzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pin-air-pump" /></template>
<style>
.akntkhbzz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 3h7M9 3v3M7 6h4v13H7ZM4.5 19h8.6M11 16.5q.532-.002.991-.123m3.252-6.368C15.185 8.295 14.723 6.723 14 6m4 15l-2.25-3.25a3.25 3.25 0 1 1 4.5 0Z");
}

</style>
