<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vfqkunl5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:waterfall-chart-sharp" /></template>
<style>
.vfqkunl5c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 12.75H5.5v7.5H2.75zm5.25-5h2.75v5H8zm5.25 0H16v3.5h-2.75zm5.25 3.5h2.75v9H18.5z");
}

</style>
