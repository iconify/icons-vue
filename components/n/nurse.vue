<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="h6j8knffq"/><path class="imf2d8btv"/><path class="vc7sutyhk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:nurse" /></template>
<style>
.h6j8knffq {
  d: path("M4 20c0-3.25 3.5-5.5 8-5.5s8 2.25 8 5.5c0 .6-.4 1-1 1H5c-.6 0-1-.4-1-1ZM8 7.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0Z");
}

.imf2d8btv {
  fill: currentColor;
  d: path("m8 5.5l.75-3h6.5l.75 3c-2.5 1-5.5 1-8 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vc7sutyhk {
  d: path("M9.75 14.75L12 18l2.25-3.25");
}

</style>
