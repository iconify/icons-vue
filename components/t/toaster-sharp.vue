<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="cch2o1edk"/><path class="n2fha8b2l"/><path class="c7hk1xptw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:toaster-sharp" /></template>
<style>
.c7hk1xptw {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 20.25v1m11-1v1");
}

.cch2o1edk {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 7.25v-4h4v4m3 0v-4h4v4M2.75 9.75h18.5v10.5H2.75zm3.5 3.75h4");
}

.n2fha8b2l {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16.75 15.25h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
