<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fh35a7umq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:three-dof" /></template>
<style>
.fh35a7umq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 15V3.5M6.75 5.75L9 3.5l2.25 2.25M9 15h11.5m-2.25-2.25L20.5 15l-2.25 2.25M9 15l-5.5 5.5m0-3v3h3m8-8a6 6 0 0 0-3-3");
}

</style>
