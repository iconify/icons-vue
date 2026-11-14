<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sgqzcirlp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:overhead-hold" /></template>
<style>
.sgqzcirlp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 2.5H7v7H3.5Zm13.5 0h3.5v7H17ZM7 6h10m-8 6.75a3 3 0 1 0 6 0a3 3 0 1 0-6 0ZM5.5 21.5c0-2.25 2.5-3 6.5-3s6.5.75 6.5 3");
}

</style>
