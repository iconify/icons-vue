<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="khv4kn3jb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:number-candle-sharp" /></template>
<style>
.khv4kn3jb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.5 2.75L15 4.4v.85a1.5 1.5 0 0 1-3 0V4.4zm-4.34 8.96l2.68-1.92l.41-.29h2.5v9.75H17v2H8v-2h2.75v-6.5l-.42.26l-1.16.73l-.42.26v-2z");
}

</style>
