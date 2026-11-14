<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xrz58rp2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:user" /></template>
<style>
.xrz58rp2i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 20c0-3.3 3.6-5.5 8-5.5s8 2.2 8 5.5c0 .6-.4 1-1 1H5c-.6 0-1-.4-1-1ZM8 7.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0Z");
}

</style>
