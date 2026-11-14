<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wlez06brp"/><path class="x5_5_neto"/><path class="waas9xbwd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:receipt-refund" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.waas9xbwd {
  d: path("m11 10l-1.5 1.5L11 13");
}

.wlez06brp {
  d: path("M6.75 3h10.5A1.75 1.75 0 0 1 19 4.75v14.234A1.17 1.17 0 0 1 17.25 20l-.882-.504a1.75 1.75 0 0 0-1.736 0l-1.764 1.008a1.75 1.75 0 0 1-1.736 0l-1.764-1.008a1.75 1.75 0 0 0-1.736 0L6.75 20A1.17 1.17 0 0 1 5 18.984V4.75A1.75 1.75 0 0 1 6.75 3M8.5 7h7");
}

.x5_5_neto {
  d: path("M9.5 11.5h4a2 2 0 0 1 0 4h-2");
}

</style>
