<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ql94d0vbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:rx-symbol" /></template>
<style>
.ql94d0vbo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 4v16M5 4h5a3.5 3.5 0 0 1 0 7H5m4.5.5l3 8.5m2.5-8l5.5 8m0-8L15 20");
}

</style>
