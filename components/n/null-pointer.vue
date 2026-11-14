<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m77o2xbip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:null-pointer" /></template>
<style>
.m77o2xbip {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.5 3.5l14 6L12 12l-2.5 6.5Zm9.25 14.25a4 4 0 1 0 8 0a4 4 0 1 0-8 0ZM15 20.5l5.5-5.5");
}

</style>
