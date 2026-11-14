<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b-32qcb5c"/><path class="b98houu0r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:wifi-6" /></template>
<style>
.b-32qcb5c {
  d: path("M3.575 7.575a10.5 10.5 0 0 1 14.85 0");
}

.b98houu0r {
  d: path("M6.05 10.05a7 7 0 0 1 9.9 0m-7.425 2.475a3.5 3.5 0 0 1 4.95 0M11 15h.01m8.208.892l1.25.682a1.5 1.5 0 0 1 .782 1.316v1.22a1.5 1.5 0 0 1-.782 1.316l-1.25.682a1.5 1.5 0 0 1-1.436 0l-1.25-.682a1.5 1.5 0 0 1-.782-1.316v-1.22a1.5 1.5 0 0 1 .782-1.316l1.25-.682a1.5 1.5 0 0 1 1.436 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
