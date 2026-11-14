<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eewqy1b8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:minimum-safe-altitude" /></template>
<style>
.eewqy1b8u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.943 17H2.5L9 3.5l4.5 6.5L16 6.5l4.784 9.133M14.75 18.5H22m-2.5 0L17 15.25m2.5 3.25L17 21.75M14.75 17v3");
}

</style>
