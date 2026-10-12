<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="b25v5acmw"/><path class="p5wc5jbhb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tomato-sharp" /></template>
<style>
.b25v5acmw {
  d: path("m12 8.25l-1.937-1.162L8 7.5c-2.75.5-4.75 3-4.75 6.5c0 4 3.75 7 8.75 7s8.75-3 8.75-7c0-3.5-2-6-4.75-6.5l-2.062-.412z");
}

.p5wc5jbhb {
  d: path("m12.15 3.32l.76 1.66l.15.31l.35.04l1.81.22l.35.04l-.26.24l-1.34 1.24l-.26.24l.07.34l.36 1.79l.06.34l-.3-.17l-1.59-.89l-.31-.17l-.31.17l-1.59.89l-.3.17l.06-.34l.36-1.79l.07-.34l-.26-.24l-1.34-1.24l-.26-.24l.35-.04l1.81-.22l.35-.04l.15-.31l.76-1.66L12 3z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
