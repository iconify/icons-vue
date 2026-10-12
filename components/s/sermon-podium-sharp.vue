<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k1b4hqciy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sermon-podium-sharp" /></template>
<style>
.k1b4hqciy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.34 6.13l15.32-3.26l.59-.12v4l-.59.08L4.34 8.92L3.75 9V6.25zM12 7.88v3.37m0 7.5v2.5m-5 0h10m-8.75-10h7.5v7.5h-7.5zm3.75 2.5v2.5m-1-1.5h2");
}

</style>
