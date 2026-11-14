<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="f7dvlb0pw"/><path class="wj22xub1h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:photo-essay" /></template>
<style>
.f7dvlb0pw {
  d: path("M2.5 2.5h12v9h-12Zm7 12h12v7h-12Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wj22xub1h {
  d: path("M5 11.5L8.5 7l3.5 4.5m0 10l3.5-4l3.5 4M14.5 7H18v7.5");
}

</style>
