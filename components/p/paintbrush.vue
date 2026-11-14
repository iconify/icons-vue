<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mdhcsi96i"/><path class="ju8iambde"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:paintbrush" /></template>
<style>
.ju8iambde {
  d: path("m9.5 11l3.5 3.5c-.5 4-5.5 6.5-10 6.5c0-4.5 2.5-9.5 6.5-10Zm4.25-.75L20.5 3.5");
}

.mdhcsi96i {
  d: path("m12 8.5l3.5 3.5l-2.5 2.5L9.5 11Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
