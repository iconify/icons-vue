<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ib5irsftq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:shoe-box-stack" /></template>
<style>
.ib5irsftq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 15.5h19v6h-19Zm1-6h17v6h-17Zm1.5-6h14v6H5ZM2.5 17.75h19m-18-6h17M5 5.75h14");
}

</style>
