<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lho7z_bag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pos-hold-sale" /></template>
<style>
.lho7z_bag {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 2.5h7.5A3.5 3.5 0 0 1 17 6v3a3.5 3.5 0 0 1-3.5 3.5H6A3.5 3.5 0 0 1 2.5 9V6A3.5 3.5 0 0 1 6 2.5m2.75 10V19m-3 0h6A1.25 1.25 0 0 1 13 20.25a1.25 1.25 0 0 1-1.25 1.25h-6a1.25 1.25 0 0 1-1.25-1.25A1.25 1.25 0 0 1 5.75 19M5.5 6h5m-5 3.25H8m3 0h3m2.25 5.5v6.5m3.5-6.5v6.5");
}

</style>
