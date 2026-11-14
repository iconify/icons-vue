<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hdx_qs_nc"/><path class="x5_5_neto"/><path class="waas9xbwd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:receipt-refund" /></template>
<style>
.hdx_qs_nc {
  d: path("M5 3h14v18l-3.5-2l-3.5 2l-3.5-2L5 21Zm3.5 4h7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.waas9xbwd {
  d: path("m11 10l-1.5 1.5L11 13");
}

.x5_5_neto {
  d: path("M9.5 11.5h4a2 2 0 0 1 0 4h-2");
}

</style>
