<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bqqupqbfa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:power-cut-candle" /></template>
<style>
.bqqupqbfa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5c1.75 1.75 2.5 3 2.5 4a2.5 2.5 0 0 1-5 0c0-1 .75-2.25 2.5-4Zm-3 9h6V19H9Zm-4 10h14");
}

</style>
