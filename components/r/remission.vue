<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g5_bfacov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:remission" /></template>
<style>
.g5_bfacov {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4 20.5l7.75-12c1.25-2 0-5.75-2.75-5.75S5 6.5 6.25 8.5l5.414 8.384M14.5 18l2.5 2.5l4.5-5");
}

</style>
