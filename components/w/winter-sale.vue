<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g--chnb2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:winter-sale" /></template>
<style>
.g--chnb2t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.5 4.304l-6 10.392m9-5.196h-12m9 5.196l-6-10.392m4.667-.192l.458 1.707l1.708-.457M15 8.25L13.75 9.5L15 10.75m-1.667 2.888l-1.708-.457l-.458 1.707m-3.334 0l-.458-1.707l-1.708.457M4 10.75L5.25 9.5L4 8.25m1.667-2.888l1.708.457l.458-1.707M15 21l6-6m-5.5.5h.01m4.99 5h.01");
}

</style>
