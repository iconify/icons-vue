<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="bicgcfb5m"/><path class="cuhmvlbkj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sparkline-sharp" /></template>
<style>
.bicgcfb5m {
  d: path("M2.75 5.75h18.5v12.5H2.75z");
}

.cuhmvlbkj {
  d: path("m6.25 13.75l2.5-2.5l2.5 2l3-4.5l3.5 3");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
