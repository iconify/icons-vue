<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gydtbsbqv"/><path class="zwy5eobsu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:panorama" /></template>
<style>
.gydtbsbqv {
  d: path("M2.5 6c6 2 13 2 19 0v12c-6-2-13-2-19 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zwy5eobsu {
  d: path("m7 14.5l3-3l2.5 2.5l2.5-2.5l2.5 2.5");
}

</style>
