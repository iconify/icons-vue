<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="hci_8kh1k"/><path class="pibz1d67m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mausoleum-sharp" /></template>
<style>
.hci_8kh1k {
  d: path("M7.5 9.75a4.5 4.5 0 0 1 9 0Zm4.5-4.5v-2.5m-9.25 18v-2H4.5V17h1V9.75h13V17h1v1.75h1.75v2.5H2.75z");
}

.pibz1d67m {
  d: path("M10 17v-4.75h4V17");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
