<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p5h65b8lw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:upload" /></template>
<style>
.p5h65b8lw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 15v3a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2v-3m-8 0V3.5M7.5 8L12 3.5L16.5 8");
}

</style>
