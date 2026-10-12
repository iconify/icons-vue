<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="p6ac3_bpv"/><path class="eam0eacoq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sold-sign-sharp" /></template>
<style>
.eam0eacoq {
  d: path("m11.75 11.5l2 2l3.5-3.75");
}

.p6ac3_bpv {
  d: path("M5.25 21.25V2.75m0 2.25h14M2.75 21.25h5M10.25 5v2.5m7-2.5v2.5m-8.5 0h11.5v8H8.75z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
