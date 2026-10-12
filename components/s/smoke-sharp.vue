<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="g27i75b0q"/><path class="dm6-i9zis"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:smoke-sharp" /></template>
<style>
.dm6-i9zis {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10.75 4.5h.01M3 7.5h.01m13.24 0h.01");
}

.g27i75b0q {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 21.25V13h4v-3h5.5v5h2.5v-4h5.5v10.25Zm0-16.75h6.5m3.25 0h8.75m-16 3h9.5m3 0h3.5");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
