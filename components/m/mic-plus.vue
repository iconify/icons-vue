<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="k1aqur_1z"/><path class="o911x5vpn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mic-plus" /></template>
<style>
.k1aqur_1z {
  d: path("M7 2.5h4a1 1 0 0 1 1 1V13a1 1 0 0 1-1 1H7a1 1 0 0 1-1-1V3.5a1 1 0 0 1 1-1Z");
}

.o911x5vpn {
  d: path("M2.5 11a6.5 6.5 0 0 0 13 0M9 17.5v4M18.5 3v6m-3-3h6");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
