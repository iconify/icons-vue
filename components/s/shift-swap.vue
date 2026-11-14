<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jsddqyx-s"/><path class="lcf-a9-tv"/><path class="a0uv8hbjr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:shift-swap" /></template>
<style>
.a0uv8hbjr {
  d: path("M2.25 14.75L4 13l1.75 1.75");
}

.jsddqyx-s {
  d: path("M4.5 6.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm13 6.5c-3 .5-4.25 3.5-3 6c1.25 2.25 4 2.75 6 1.25c-2.75-.5-4-4-3-7.25ZM6.5 2v1m0 7v1M2 6.5h1m7 0h1m2.5-2c4 0 6.5 2.5 6.5 6.5");
}

.lcf-a9-tv {
  d: path("M18.25 9.25L20 11l1.75-1.75M10.5 19.5C6.5 19.5 4 17 4 13");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
