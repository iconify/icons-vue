<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="g88u-mb_j"/><path class="hw2p_8bff"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:outlet-cover" /></template>
<style>
.g88u-mb_j {
  d: path("M5.5 2.5h13v19h-13Zm5 3.5v3m3-3v3");
}

.hw2p_8bff {
  d: path("M8.5 12.5h7v6h-7Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
