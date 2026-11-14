<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lq78gvbck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:wrestling-singlet" /></template>
<style>
.lq78gvbck {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 2.5H10q2 3 4 0h2.5l.5 6c1.5 1.5 1.5 4 1 6.5q-3 3-4.5 6h-3Q9 18 6 15c-.5-2.5-.5-5 1-6.5Zm-.5 6h10");
}

</style>
