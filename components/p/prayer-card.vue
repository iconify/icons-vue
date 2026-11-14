<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lw382ibye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:prayer-card" /></template>
<style>
.lw382ibye {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 19.5V7a8 8 0 0 1 13 0v12.5a2 2 0 0 1-2 2h-9a2 2 0 0 1-2-2Zm3-7.5h7m-7 4h5");
}

</style>
