<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l3dd8bc3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mold" /></template>
<style>
.l3dd8bc3r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 8.5C2.75 5 5.5 2.75 8.5 3c3.25 0 5 2.5 4.5 5c.25 3-2 5.25-5 5c-3.25.5-5-1.75-5-4.5Zm10 9c-.25-3 2-4.75 4.5-4.5c2.75 0 3.75 2.25 3.5 4.25c0 2.5-2 4-4.25 3.75c-2.25.25-3.75-1.25-3.75-3.5Zm-8.75 1a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0ZM17.5 6h.01m2.99 3.25h.01");
}

</style>
