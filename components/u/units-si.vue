<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z8foi0h6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:units-si" /></template>
<style>
.z8foi0h6o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 13h19v7h-19ZM6 13v3.75M9 13v2m3-2v3.75M15 13v2m3-2v3.75M4.5 3v7m4-4.5l-4 2.75l4 1.75m3.5 0V6.5a1.75 1.75 0 0 1 3.5 0V10m0-3.5a1.75 1.75 0 0 1 3.5 0V10");
}

</style>
