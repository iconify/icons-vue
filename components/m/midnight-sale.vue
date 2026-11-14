<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v1tpmbhzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:midnight-sale" /></template>
<style>
.v1tpmbhzb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.5 3.5a9 9 0 1 0 9 9a6.5 6.5 0 0 1-9-9Zm3 7l5-5M15 6h.01M19 10h.01");
}

</style>
