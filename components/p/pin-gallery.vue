<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="t5z_zxb8m"/><path class="ezc_z5bls"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pin-gallery" /></template>
<style>
.ezc_z5bls {
  d: path("m6.5 18l4-4.5l4 4.5m1-6h.01");
}

.t5z_zxb8m {
  d: path("M3 8h18v13H3Zm4.5 0L12 3.5L16.5 8");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
