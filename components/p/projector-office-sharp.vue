<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pf4aaob_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:projector-office-sharp" /></template>
<style>
.pf4aaob_w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 15.75h16.5v5.5H3.75zm2-3h12.5v3H5.75zm6.25 0v-4M8.92 6.41l4.66-2.32l.67-.34l.37.65l.26.45l.37.65l-.67.34l-4.66 2.32l-.67.34l-.37-.65l-.26-.45l-.37-.65zm9.33-3.66h3v6.5h-3z");
}

</style>
