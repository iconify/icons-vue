<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m7kmcdbqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:motocross-boots" /></template>
<style>
.m7kmcdbqp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 3h10l-1 4v5.5l5 2a2.5 2.5 0 0 1 2 2.5v1H5.5l1-11Zm.5 15v3H21v-3M6.25 10.5H14");
}

</style>
