<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kc_4-lb1c"/><path class="t5qd4qb6h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:oil-can" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kc_4-lb1c {
  d: path("M7 11h5a3.5 3.5 0 0 1 3.5 3.5V18a3.5 3.5 0 0 1-3.5 3.5H7A3.5 3.5 0 0 1 3.5 18v-3.5A3.5 3.5 0 0 1 7 11");
}

.t5qd4qb6h {
  d: path("m6.75 9.75l.313-.522A1.5 1.5 0 0 1 8.349 8.5h2.302a1.5 1.5 0 0 1 1.286.728l.313.522a.825.825 0 0 1-.708 1.25H7.458a.825.825 0 0 1-.708-1.25M11.5 8.5l9-5.5");
}

</style>
