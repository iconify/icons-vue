<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m2xvz6bvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sea-ice" /></template>
<style>
.m2xvz6bvx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12.5h19m-18 0l1.5-5l4.5-1l1 6Zm10 0L15 9l4-.5l1.5 4Zm-9 4q2-1.5 4 0t4 0t4 0t3 .5");
}

</style>
