<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wvnquhbnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:potty-training-sharp" /></template>
<style>
.wvnquhbnb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 3h4.5v8.75H5zm-.25 8.75h15.5v1c0 3.6-2.9 6.25-6.5 6.25h-3.5c-3.6 0-6.5-2.65-6.5-6.25v-1zM8 21.25h8");
}

</style>
