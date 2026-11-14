<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w351e2bdt"/><path class="gzfsbeezp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:nft-auction" /></template>
<style>
.gzfsbeezp {
  d: path("M15.5 20.5L18 18l3.5 3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w351e2bdt {
  d: path("m13.5 4.214l3.536 3.536a2.5 2.5 0 0 1 0 3.536a2.5 2.5 0 0 1-3.536 0L9.964 7.75a2.5 2.5 0 0 1 0-3.536a2.5 2.5 0 0 1 3.536 0M11.75 9.5L6.5 14.75m-1.875 3h5.75A1.625 1.625 0 0 1 12 19.375A1.625 1.625 0 0 1 10.375 21h-5.75A1.625 1.625 0 0 1 3 19.375a1.625 1.625 0 0 1 1.625-1.625M17.25 16h2.5a1.75 1.75 0 0 1 1.75 1.75v2a1.75 1.75 0 0 1-1.75 1.75h-2.5a1.75 1.75 0 0 1-1.75-1.75v-2A1.75 1.75 0 0 1 17.25 16");
}

</style>
