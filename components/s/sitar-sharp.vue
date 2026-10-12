<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="m7t8mzb_c"/><path class="npz8syh8u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sitar-sharp" /></template>
<style>
.m7t8mzb_c {
  cx: 7.5px;
  cy: 16.5px;
  r: 4.75px;
}

.npz8syh8u {
  d: path("M5.5 16.75L7.75 19m4.52-5.51l7.58-7.58l.53-.53l-.53-.53l-.7-.7l-.53-.53l-.53.53l-7.58 7.58l-.53.53l.53.53l.7.7l.53.53zm4.13-7.64l-1.2-1.2m-.8 3.2l-1.2-1.2");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
