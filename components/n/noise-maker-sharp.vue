<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x_zlzfo3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:noise-maker-sharp" /></template>
<style>
.x_zlzfo3j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 10.25h3v3.5h-3zm3 1.75h7.5m.92-1.59l6.41-3.32l.67-.34v10.5l-.67-.34l-6.41-3.32l-.67-.34v-2.5zm3.33-.66v4.5");
}

</style>
