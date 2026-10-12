<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="hf_7whbfu"/><path class="iu64uzbji"/><circle class="wft9rcgmo"/><circle class="w8vso_bht"/><path class="mvfj32gkh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sheep-shearing-sharp" /></template>
<style>
.hf_7whbfu {
  d: path("m14.5 16.25l1.358 2.143l-2.528-.213a1.76 1.76 0 0 1-2.96 1.02A1.9 1.9 0 0 1 7 18.85a1.51 1.51 0 0 1-2.2-1.57l-2.074-1.03L4.8 15.22A1.51 1.51 0 0 1 7 13.65a1.9 1.9 0 0 1 3.37-.35a1.76 1.76 0 0 1 2.96 1.02l2.528-.213z");
}

.iu64uzbji {
  d: path("M5.83 13.76a1.5 2.25 35 1 0-2.46-1.72a1.5 2.25 35 1 0 2.46 1.72Zm1.42 5.99v1.5m4.5-1.5v1.5");
}

.mvfj32gkh {
  d: path("M17.4 5.6L9.75 9.5m7.65 1.4L9.75 7");
}

.w8vso_bht {
  cx: 19.25px;
  cy: 11.75px;
  r: 2px;
}

.wft9rcgmo {
  cx: 19.25px;
  cy: 4.75px;
  r: 2px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
