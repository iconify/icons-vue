<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x0p0eqbyv"/><path class="r32gd66qb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:zoho-daybook" /></template>
<style>
.r32gd66qb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.963 11.624h3.688c3.373 0 6.108 2.74 6.108 6.12s-2.735 6.122-6.108 6.122l6.108 5.98");
}

.x0p0eqbyv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.887 32.355V9.08a3.58 3.58 0 0 1 3.58-3.581h25.065a3.58 3.58 0 0 1 3.58 3.58v22.678a3.58 3.58 0 0 1-3.58 3.58H11.468a3.58 3.58 0 0 0 0 7.162h25.064a3.58 3.58 0 0 0 3.58-3.58M17.963 17.775h12.074m-8.386-6.151h8.386");
}

</style>
