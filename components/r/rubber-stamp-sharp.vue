<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xqaty3b5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:rubber-stamp-sharp" /></template>
<style>
.xqaty3b5b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.75 2.75h8.5v3h-8.5zm0 1.5h-4v14m12.5-14h4v14M6.75 8h10.5v7.5H6.75zm2.75 3.75h5m-2.5-6V8m-6.25 9.75h12.5v3.5H5.75z");
}

</style>
