<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cevil409r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:satellite-downlink" /></template>
<style>
.cevil409r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 3h4v7h-4ZM2.5 4.5H7v4H2.5Zm14.5 0h4.5v4H17Zm-10 2h3m4 0h3m-2.525 5.975a3.5 3.5 0 0 1-4.95 0m3.607 3.926q-.49.086-.988.097q-.497.011-.991-.053q-.493-.065-.971-.204q-.478-.14-.929-.35M18 14.5v7m-3-3l3 3l3-3");
}

</style>
