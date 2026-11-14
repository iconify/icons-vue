<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fn5zgb_po"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pin-ferry" /></template>
<style>
.fn5zgb_po {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12.5h19l-2.5 5H5Zm3.5 0V8a1 1 0 0 1 1-1h8l2.5 5.5M9 3h3v4H9ZM3 21q2.25-1.5 4.5 0t4.5 0t4.5 0t4.5 0");
}

</style>
