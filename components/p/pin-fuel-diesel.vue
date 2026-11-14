<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="id2pidcpj"/><path class="z4_q8b9ix"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pin-fuel-diesel" /></template>
<style>
.id2pidcpj {
  d: path("M13.4 21H3.5V3h10v9.2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z4_q8b9ix {
  d: path("M6.5 6h4v3.5h-4Zm7 5H16a1.5 1.5 0 0 0 1.5-1.5V6a1.5 1.5 0 0 1 3 0v5.5M16.25 15H18a3.25 3.25 0 0 1 0 6.5h-1.75Z");
}

</style>
