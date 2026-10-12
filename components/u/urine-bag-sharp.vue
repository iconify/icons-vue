<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lrsiu3b_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:urine-bag-sharp" /></template>
<style>
.lrsiu3b_l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 7.5h13v12H5zm10 3h-2.5m2.5 3h-1.5m1.5 3h-2.5m-1-9V2.75H8V4.5m0 15v1.75");
}

</style>
