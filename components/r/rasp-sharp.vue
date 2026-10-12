<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="b18b7p8wn"/><path class="etcpiyqid"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:rasp-sharp" /></template>
<style>
.b18b7p8wn {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.15 16.67l1.76-1.76l1.24-1.24l1.24 1.24l.7.7l1.24 1.24l-1.24 1.24l-1.76 1.76l-1.24 1.24l-1.24-1.24l-.7-.7l-1.24-1.24zm3.57-3.84l9.47-8.23l.75-.66l.71.71l.7.7l.71.71l-.66.75l-8.23 9.47l-.66.75l-.71-.71l-2.12-2.12l-.71-.71z");
}

.etcpiyqid {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M11.22 12.78h.01m2.64-2.65h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
