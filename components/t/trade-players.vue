<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k1i2wvglt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:trade-players" /></template>
<style>
.k1i2wvglt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 11.25a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0ZM2.5 21.5c0-2.75 1.75-5 4-5s4 2.25 4 5M15 11.25a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0ZM13.5 21.5c0-2.75 1.75-5 4-5s4 2.25 4 5M6.5 6q5.5-5.5 11 0m-11-2.75V6h2.75m8.25-2.75V6h-2.75");
}

</style>
