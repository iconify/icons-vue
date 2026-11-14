<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jxd344b3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:milk-jug-plastic" /></template>
<style>
.jxd344b3h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 8L8 5V3h5v2l2.5 3v11.5A1.5 1.5 0 0 1 14 21H7a1.5 1.5 0 0 1-1.5-1.5Zm10 2H17a1.5 1.5 0 0 1 1.5 1.5v3A1.5 1.5 0 0 1 17 16h-1.5M8 13h5");
}

</style>
