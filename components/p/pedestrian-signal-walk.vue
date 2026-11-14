<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o72zbacef"/><path class="eyrmcjcvb"/><path class="ofw-vbs-c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pedestrian-signal-walk" /></template>
<style>
.eyrmcjcvb {
  d: path("M11.5 6a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m1 3L11 13.25l2.25 2.25V19M11 13.25l-1.25 3l-1.5 2.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o72zbacef {
  d: path("M8.875 2.5h6.25A4.375 4.375 0 0 1 19.5 6.875v10.25a4.375 4.375 0 0 1-4.375 4.375h-6.25A4.375 4.375 0 0 1 4.5 17.125V6.875A4.375 4.375 0 0 1 8.875 2.5");
}

.ofw-vbs-c {
  d: path("m8.75 11l3-2l3 2.5");
}

</style>
