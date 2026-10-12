<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sbcp36jkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:spa-stones-sharp" /></template>
<style>
.sbcp36jkx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 4.25a3.5 1.5 0 1 0 7 0a3.5 1.5 0 1 0-7 0ZM6 10.75a6 2 0 1 0 12 0a6 2 0 1 0-12 0ZM3.5 18.5a8.5 2.75 0 1 0 17 0a8.5 2.75 0 1 0-17 0Z");
}

</style>
