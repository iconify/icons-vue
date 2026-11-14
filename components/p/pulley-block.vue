<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bskzvx8ts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pulley-block" /></template>
<style>
.bskzvx8ts {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 2.5h6m-3 0V4M6 9a5 5 0 1 0 10 0A5 5 0 1 0 6 9Zm0 0v12.5M16 9v6.5M11 9h.01M13 15.5h6V21h-6Z");
}

</style>
