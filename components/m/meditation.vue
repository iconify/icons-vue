<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sdv_6ibqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:meditation" /></template>
<style>
.sdv_6ibqg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 4.75a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0ZM7.5 15.5c0-4 2-5.75 4.5-5.75s4.5 1.75 4.5 5.75m-13 3c0-2 3-3 8.5-3s8.5 1 8.5 3c0 1.25-1 2-2.5 2H6c-1.5 0-2.5-.75-2.5-2Z");
}

</style>
