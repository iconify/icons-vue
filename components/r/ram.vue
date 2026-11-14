<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ipu8eku9c"/><path class="n5xigcpwn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ram" /></template>
<style>
.ipu8eku9c {
  d: path("M2 6.5h20v9H2Z");
}

.n5xigcpwn {
  d: path("M5 9.5h3v3H5Zm5.5 0h3v3h-3Zm5.5 0h3v3h-3Zm-10.5 6v3m3-3v3m7-3v3m3-3v3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
