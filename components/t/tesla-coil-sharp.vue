<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o0xovqb4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tesla-coil-sharp" /></template>
<style>
.o0xovqb4z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 3.25h12.5v4.5H5.75zm3.5 4.5h5.5V18.5h-5.5zm0 3.25h5.5m-5.5 3.75h5.5m-7.5 3.75h9.5v2.75h-9.5zM5 10l-1.75 2.5h2.5L4 15.25M19 10l1.75 2.5h-2.5L20 15.25");
}

</style>
