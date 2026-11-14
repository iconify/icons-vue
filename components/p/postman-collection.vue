<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ih1lrlw7a"/><path class="oqervpm8v"/><path class="xwbhlkbed"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:postman-collection" /></template>
<style>
.ih1lrlw7a {
  d: path("M3 11a2 2 0 0 1 2-2h3.5l2 2H19a2 2 0 0 1 2 2v6.5a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2Z");
}

.oqervpm8v {
  d: path("M11.5 11V7.5A1.5 1.5 0 0 1 13 6h2a1.5 1.5 0 0 1 1.5 1.5V11");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xwbhlkbed {
  d: path("M19.5 11V4.5A1.5 1.5 0 0 0 18 3h-3a1.5 1.5 0 0 0-1.5 1.5V6");
}

</style>
