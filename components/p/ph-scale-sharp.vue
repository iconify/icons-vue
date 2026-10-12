<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h0ol66vlk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ph-scale-sharp" /></template>
<style>
.h0ol66vlk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 11h18.5v6.5H2.75zm3.7 0v6.5m3.7-6.5v6.5m3.7-6.5v6.5m3.7-6.5v6.5M10.5 3.75h3.75l-.37.65l-1.51 2.7l-.37.65l-.37-.65l-1.51-2.7l-.37-.65z");
}

</style>
