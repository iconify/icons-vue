<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z7bqdjmlg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:year-view-sharp" /></template>
<style>
.z7bqdjmlg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 3.25h7v7h-7zm0 2.75h7m3.5-2.75h7v7h-7zm0 2.75h7m-17.5 7.75h7v7h-7zm0 2.75h7m3.5-2.75h7v7h-7zm0 2.75h7");
}

</style>
