<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gibxw12mx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:workshop-room" /></template>
<style>
.gibxw12mx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12h19v2.5h-19Zm2 2.5v7m15-7v7M13 5h4v7h-4ZM7.5 6h3v6h-3Zm-4 3h4m-4-2.5v5");
}

</style>
