<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bsohlcpxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sort-alpha" /></template>
<style>
.bsohlcpxt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 6.5H10M3.75 12H10m-6.25 5.5H10m4.5 1.75V4.75m-2 2l2-2l2 2m2.5-2v14.5m-2-2l2 2l2-2");
}

</style>
