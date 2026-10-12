<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="tefs7d_ao"/><path class="hfr86bw5l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tablet-landscape-sharp" /></template>
<style>
.hfr86bw5l {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18.25 12h.01");
}

.tefs7d_ao {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 4h18.5v16H2.75z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
