<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="on_s14bcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:overpass-sharp" /></template>
<style>
.on_s14bcq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.25 2.75h7.5v18.5h-7.5zM12 5.25v2.5m0 3v2.5m0 3v2.5m-9.25-10H6.5m11 0h3.75m-18.5 6.5H6.5m11 0h3.75");
}

</style>
