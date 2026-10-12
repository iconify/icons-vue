<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="l5g864bjc"/><path class="ipxfp0b5v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:transformer-block-sharp" /></template>
<style>
.ipxfp0b5v {
  d: path("M7.75 5.75h8.5v4.5h-8.5zm1.5 8h7v4.5h-8.5v-4.5zm2.75-3.5v3.5M18.75 8h2.5v8h-2.5");
}

.l5g864bjc {
  d: path("M5.25 2.75h13.5v18.5H5.25z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
