<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uz8r2wbef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:surgical-robot" /></template>
<style>
.uz8r2wbef {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 2.5h19v3h-19Zm5.5 3v3M9.25 11L14 15m-7.5-5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm7.25 6a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm1.5 1.5v2m-1.5 2l1.5-2l1.5 2");
}

</style>
