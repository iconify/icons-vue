<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="q8_11iq6n"/><path class="kk680c1tx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:visitor-pass" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kk680c1tx {
  d: path("m9.5 13l2.5 5.5l2.5-5.5");
}

.q8_11iq6n {
  d: path("M10 7h4a3.5 3.5 0 0 1 3.5 3.5V18a3.5 3.5 0 0 1-3.5 3.5h-4A3.5 3.5 0 0 1 6.5 18v-7.5A3.5 3.5 0 0 1 10 7m.5 2.75h3M4 2.5C6 5.5 8.5 7 12 7s6-1.5 8-4.5");
}

</style>
