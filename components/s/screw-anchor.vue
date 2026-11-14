<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m_2akfb4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:screw-anchor" /></template>
<style>
.m_2akfb4i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 7.5v9l-3-2v-5Zm0 3h3.5m-3.5 3h3.5m0-6h12v9h-12Zm0-4.5v18m4-13.5v9m4-9v9");
}

</style>
