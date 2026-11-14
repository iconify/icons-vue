<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="p-_sw8--k"/><path class="k8876snol"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:screen-mirror" /></template>
<style>
.k8876snol {
  d: path("m9.5 17.75l1.75 1.75l-1.75 1.75m5-10.25h7v10.5h-7Z");
}

.p-_sw8--k {
  d: path("M11.7 13H2.5V2.5H18v5.7M5.5 16A3.5 3.5 0 0 0 9 19.5h2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
