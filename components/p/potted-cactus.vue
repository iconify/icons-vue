<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rck-m6biw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:potted-cactus" /></template>
<style>
.rck-m6biw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 14.5h13l-1.75 7h-9.5Zm4.5 0V5a2 2 0 0 1 4 0v9.5m-4-3H8.5A1.5 1.5 0 0 1 7 10V7m7 2.5h1.5A1.5 1.5 0 0 0 17 8V5.5");
}

</style>
