<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ppm9jta7x"/><path class="a72wtzb_v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:prosthetic-leg" /></template>
<style>
.a72wtzb_v {
  fill: currentColor;
  d: path("M5.5 19.75H12v1.75H5.5Z");
}

.ppm9jta7x {
  d: path("M7 2.5L8 10h6l1-7.5M11 10c0 3 3.5 4.5 4.5 7.5c.75 2.5-1 4-3.5 4H6M7.5 5.75h7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
