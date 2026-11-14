<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="knxtrwbwf"/><path class="f76uqbbth"/><path class="fipq7ybjz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:turntable-product" /></template>
<style>
.f76uqbbth {
  d: path("M9 4h6v9H9ZM3.75 18a9.5 4.75 0 0 0 16.5 0");
}

.fipq7ybjz {
  d: path("m18 17.75l2.25.25l-.25 2.25");
}

.knxtrwbwf {
  d: path("M9 10.25A9 3 0 0 0 3 13a9 3 0 0 0 18 0a9 3 0 0 0-6-2.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
