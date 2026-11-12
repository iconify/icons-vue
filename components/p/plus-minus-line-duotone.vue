<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="jsj8gunlj"/><path class="mzmeouzvr"/><path class="ifpcpz80t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:plus-minus-line-duotone" /></template>
<style>
.ifpcpz80t {
  d: path("M10.5 8.00002H8M8 8.00002L5.5 8.00002M8 8.00002L8 5.5M8 8.00002L8 10.5");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jsj8gunlj {
  d: path("M20.5355 3.46447C19.0711 2 16.714 2 12 2C7.28595 2 4.92893 2 3.46447 3.46447C2 4.92893 2 7.28595 2 12C2 16.714 2 19.0711 3.46447 20.5355M20.5355 3.46447C22 4.92893 22 7.28595 22 12C22 16.714 22 19.0711 20.5355 20.5355C19.0711 22 16.714 22 12 22C7.28595 22 4.92893 22 3.46447 20.5355M20.5355 3.46447L3.46447 20.5355");
}

.mzmeouzvr {
  d: path("M18 17H13");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
