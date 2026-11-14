<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="frcdte_bl"/><path class="llv4qgaxq"/><path class="iwj8rd4ih"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pay-period" /></template>
<style>
.frcdte_bl {
  d: path("M8 12a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm4-1.25v2.5");
}

.iwj8rd4ih {
  d: path("m16.75 18.25l-2 1.75l2 1.5m-9.5-19l2 1.5l-2 1.5");
}

.llv4qgaxq {
  d: path("M14.907 4.013a8.5 8.5 0 0 1 0 15.974m-5.814 0a8.5 8.5 0 0 1 0-15.974");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
