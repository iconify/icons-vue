<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ki5489pxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:waders" /></template>
<style>
.ki5489pxf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 6h9v6.5L16 19h3a1.5 1.5 0 0 1 1.5 1.5v.5h-8l-.5-7l-.5 7h-8v-.5A1.5 1.5 0 0 1 5 19h3l-.5-6.5Zm1 0L9 2.5M15.5 6L15 2.5");
}

</style>
