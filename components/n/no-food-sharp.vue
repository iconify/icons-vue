<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dxsifqirj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:no-food-sharp" /></template>
<style>
.dxsifqirj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 13.25v3m3-3V21m3-7.75v3m0 0a3 3 0 0 1-6 0M17 3l2.75 1.571V10H17Zm0 7v3.75m-13.25-10l16.5 16.5");
}

</style>
