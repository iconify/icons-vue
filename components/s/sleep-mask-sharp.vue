<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="l2a6sjbyj"/><path class="ncgeo9bwd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sleep-mask-sharp" /></template>
<style>
.l2a6sjbyj {
  d: path("M15.75 2.75h3.5l-3.5 3.5h3.5M2.75 12V8.5h18.5v4c0 3-2.1 5-4.75 5c-2 0-3.1-1.5-4.5-1.5s-2.5 1.5-4.5 1.5c-2.65 0-4.75-2-4.75-5Z");
}

.ncgeo9bwd {
  d: path("m5.75 12.5l1.875 1.534L9.5 12.5m5 0l1.875 1.534L18.25 12.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
