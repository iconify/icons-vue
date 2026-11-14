<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c088z1j4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:training-shoes" /></template>
<style>
.c088z1j4s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 18.5v-10A1.5 1.5 0 0 1 4.5 7h3c.5 2 2 3.5 4.5 4l4.5 1c3 .75 4.5 2.5 4.5 5v1.5Zm0-3h18m-11-5l1.25-1.75M13 11.5l1.25-1.75");
}

</style>
