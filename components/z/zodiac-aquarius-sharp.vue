<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x4x3lfxui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:zodiac-aquarius-sharp" /></template>
<style>
.x4x3lfxui {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 10L6.5 7.25L9.25 10L12 7.25L14.75 10l2.75-2.75L20.25 10m-16.5 7l2.75-2.75L9.25 17L12 14.25L14.75 17l2.75-2.75L20.25 17");
}

</style>
