<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oa_fdsg0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pet-nutrition" /></template>
<style>
.oa_fdsg0o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.581 15H4.25L2.5 8.5h15l-1.326 4.925M4 8.5a2.5 2.5 0 0 1 4.5-2a3 3 0 0 1 5-.5A2.75 2.75 0 0 1 16 8.5m.25 11.75C15.75 16.5 18 14.5 22 14.5c0 4-2 6.25-5.75 5.75ZM15 21.75l4-4");
}

</style>
