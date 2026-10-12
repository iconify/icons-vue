<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r9xn1eb-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:travel-bag-sharp" /></template>
<style>
.r9xn1eb-r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 9c0-4.5 7-4.5 7 0M2.75 9h18.5v11H2.75zm4.5.5v10m9.5-10v10m-7.25-7h5");
}

</style>
