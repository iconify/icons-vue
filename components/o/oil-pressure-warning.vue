<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g96sx_bme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:oil-pressure-warning" /></template>
<style>
.g96sx_bme {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 9.5h5.75L20.5 7l-5 7.25c-.25.5-.75.75-1.25.75H8a1 1 0 0 1-1-1Zm0 1H4.5a1 1 0 0 0-1 1v.5c0 .5.25.75.75 1L7 14m3-4.5v-2m-1.5 0h3m8.5 4s-1.25 1.75-1.25 2.75a1.25 1.25 0 0 0 2.5 0c0-1-1.25-2.75-1.25-2.75Z");
}

</style>
