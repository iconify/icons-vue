<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="xgt97b4ir"/><path class="lim_vp77k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ring-heart-sharp" /></template>
<style>
.lim_vp77k {
  d: path("M10 2.75h4.75l.46.59l.83 1.07l.46.59l-.56.5l-3.38 3L12 9l-.56-.5l-3.38-3L7.5 5l.46-.59l.83-1.07l.46-.59z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xgt97b4ir {
  d: path("M5.75 15a6.25 6.25 0 1 0 12.5 0a6.25 6.25 0 1 0-12.5 0");
}

</style>
