<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="ox05rfewb"/><path class="vgi7r_3nt"/><path class="v4n1tib0v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:negative-strip-sharp" /></template>
<style>
.ox05rfewb {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 4.75h18.5v14.5H2.75z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.v4n1tib0v {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 10h5.5v4h-5.5zm8 0h5.5v4h-5.5z");
}

.vgi7r_3nt {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 7.25h.01m3.99 0h.01m3.99 0h.01m3.99 0h.01M6 16.75h.01m3.99 0h.01m3.99 0h.01m3.99 0h.01");
}

</style>
