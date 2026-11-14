<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vngkfefhw"/><path class="xncuyrj0j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:permit-holders-sign" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vngkfefhw {
  d: path("M2.5 2.5h19v13h-19Zm9.5 13v6");
}

.xncuyrj0j {
  d: path("M6.5 12.5v-7H8a2 2 0 0 1 0 4H6.5m6-.5l2 2l4-4");
}

</style>
