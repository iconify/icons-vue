<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sj0bgzb4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:torah-scroll-sharp" /></template>
<style>
.sj0bgzb4i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 4.75h4v14.5h-4zm12.5 0h4v14.5h-4zM7.75 6h8.5v12h-8.5ZM10 9h4m-4 3h4m-4 3h4M5.75 4.75v-2m12.5 2v-2m-12.5 16.5v2m12.5-2v2");
}

</style>
