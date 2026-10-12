<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="xde_ksb-v"/><path class="ngy9n_01x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:parka-sharp" /></template>
<style>
.ngy9n_01x {
  d: path("M6.5 7.75C6 5 7.25 3.5 9 3.75l1.5-1.125L12 3.75l1.5-1.125L15 3.75c1.75-.25 3 1.25 2.5 4m-11.25 4v9.5m11.5-9.5v9.5M6.25 14.5h11.5M6.25 18h11.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xde_ksb-v {
  d: path("M9.75 6.75h5.75l1.16.48l1.93.79l1.16.48l.16 1.24l1.18 9.27l.16 1.24l-1.2.34l-1.1.32l-1.2.34H6.25l-1.2-.34l-1.1-.32l-1.2-.34l.16-1.24l1.18-9.27l.16-1.24l1.16-.48l1.93-.79l1.16-.48z");
}

</style>
