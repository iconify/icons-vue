<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="bkc9cjaff"/><path class="v8g1hmbbw"/><path class="mfjc_kq7a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:single-board-computer-sharp" /></template>
<style>
.bkc9cjaff {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 4.25h18.5v15.5H2.75z");
}

.mfjc_kq7a {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 11h5.5v5.5h-5.5zm9 1.25h2.5m-2.5 3h2.5");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.v8g1hmbbw {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.5 7.5h.01m2.74 0h.01m2.74 0h.01m2.74 0h.01m2.74 0h.01");
}

</style>
