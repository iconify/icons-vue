<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e91p_bb0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sunglasses-sharp" /></template>
<style>
.e91p_bb0l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 9.75h6.5v2.75a3.75 3.75 0 0 1-7.5 0V9.75zm11 0h6.5v2.75a3.75 3.75 0 0 1-7.5 0V9.75zM10.25 11L12 9.688L13.75 11M3 9.75l2-4m16 4l-2-4m-13.75 7.5L7 11.5m9.25 1.75L18 11.5");
}

</style>
