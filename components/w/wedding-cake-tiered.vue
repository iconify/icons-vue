<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yli0nsg_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:wedding-cake-tiered" /></template>
<style>
.yli0nsg_z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 4h7v5.5h-7ZM6 9.5h12V15H6ZM3.5 15h17v6h-17Zm5-8.25h7M6 12.25h12M3.5 18h17");
}

</style>
