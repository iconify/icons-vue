<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i9tkn357e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:upward-feedback" /></template>
<style>
.i9tkn357e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 6h9.5A1.5 1.5 0 0 1 15 7.5v7a1.5 1.5 0 0 1-1.5 1.5h-5l-3 3v-3H4a1.5 1.5 0 0 1-1.5-1.5v-7A1.5 1.5 0 0 1 4 6Zm1.5 5H12m7 8V3.5m-2.25 2.25L19 3.5l2.25 2.25");
}

</style>
