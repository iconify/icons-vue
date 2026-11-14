<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vkupccguv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:palate-expander" /></template>
<style>
.vkupccguv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 2.75C5 3 2.75 8 2.75 13.5v7h3.5v-7c0-4 1.75-7 4.25-7.25Zm3 0C19 3 21.25 8 21.25 13.5v7h-3.5v-7c0-4-1.75-7-4.25-7.25ZM6.25 12.5H10m0-1.75h4v3.5h-4Zm4 1.75h3.75");
}

</style>
