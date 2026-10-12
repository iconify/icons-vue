<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w51lqzbya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sort-sharp" /></template>
<style>
.w51lqzbya {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 6.5H10M3.75 12H10m-6.25 5.5H10m4.5 1.75V4.75m-2 2l2-2l2 2m2.5-2v14.5m-2-2l2 2l2-2");
}

</style>
