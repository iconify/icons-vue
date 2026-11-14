<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="drxu1ilga"/><path class="tfl15vblw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mountain-home" /></template>
<style>
.drxu1ilga {
  d: path("M2.5 14L12 2.5L21.5 14m-17-2.5v10m15-10v10m-17 0h19m-19-5h19");
}

.tfl15vblw {
  d: path("m12 6.5l2.25 3.5h-4.5Zm-1.5 15V19h3v2.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
