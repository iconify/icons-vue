<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vqfpu5uew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mortgage-repayment-types" /></template>
<style>
.vqfpu5uew {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12 3.5l-8 7v10h8m0-17l1.5 1.25m1.5 1.5l1.5 1.25M18 8.75L19.5 10m.5 1.75v2m0 2v2m0 2v.75h-1.25m-2 0h-2m-2 0H12m0-17v17");
}

</style>
