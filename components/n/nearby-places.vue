<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="m1m7xb7jv"/><path class="hx1hd2y9u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:nearby-places" /></template>
<style>
.hx1hd2y9u {
  d: path("M10.25 8a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0ZM7.5 15.5C4.5 16 3 16.9 3 18c0 1.75 4 3 9 3s9-1.25 9-3c0-1.1-1.5-2-4.5-2.5");
}

.m1m7xb7jv {
  d: path("M12 16s-5-4-5-8a5 5 0 0 1 10 0c0 4-5 8-5 8Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
