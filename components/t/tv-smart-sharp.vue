<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="l6y_2qqgo"/><path class="nluct8bsw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tv-smart-sharp" /></template>
<style>
.l6y_2qqgo {
  d: path("M2.75 3.75h18.5v13.5H2.75zM7 17.25l-1.25 4m11.25-4l1.25 4");
}

.nluct8bsw {
  d: path("M10.5 8.25v4.5l3.75-2.25Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
