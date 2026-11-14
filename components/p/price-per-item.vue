<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ceqe5bb4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:price-per-item" /></template>
<style>
.ceqe5bb4x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 3.5h8.5v17H3Zm0 3h8.5M3 17.5h8.5m0-9l6 3m-3 3l3-3l3 3v6h-6Zm3 .75h.01");
}

</style>
