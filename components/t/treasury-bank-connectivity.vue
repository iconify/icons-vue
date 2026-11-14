<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w3_3i7bdr"/><path class="j8a5_e5qf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:treasury-bank-connectivity" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j8a5_e5qf {
  d: path("m17.055 15.823l1.768-1.768a1.5 1.5 0 0 1 2.122 0a1.5 1.5 0 0 1 0 2.122l-1.768 1.768a1.5 1.5 0 0 1-2.122 0a1.5 1.5 0 0 1 0-2.122");
}

.w3_3i7bdr {
  d: path("m7.5 5.5l3.65-2.028a1.75 1.75 0 0 1 1.7 0L16.5 5.5a1.334 1.334 0 0 1-.648 2.5H8.148A1.334 1.334 0 0 1 7.5 5.5M3 20h7.8M6 11v6m4-6v6m4-6v3.9m.055 3.923l1.768-1.768a1.5 1.5 0 0 1 2.122 0a1.5 1.5 0 0 1 0 2.122l-1.768 1.768a1.5 1.5 0 0 1-2.122 0a1.5 1.5 0 0 1 0-2.122");
}

</style>
