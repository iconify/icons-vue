<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="va3gspb5u"/><path class="q_33wpbbe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ounce-weight" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q_33wpbbe {
  d: path("m7.158 13.026l1-3A1.5 1.5 0 0 1 9.581 9h4.838a1.5 1.5 0 0 1 1.423 1.026l1 3A1.5 1.5 0 0 1 15.419 15H8.581a1.5 1.5 0 0 1-1.423-1.974");
}

.va3gspb5u {
  d: path("m3.153 15.76l2.48-8.5A1.75 1.75 0 0 1 7.313 6h9.375a1.75 1.75 0 0 1 1.679 1.26l2.48 8.5a1.75 1.75 0 0 1-1.68 2.24H4.833a1.75 1.75 0 0 1-1.68-2.24");
}

</style>
