<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ncbein6kj"/><path class="lr3iu7b5i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pin-paint" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lr3iu7b5i {
  d: path("M18 5.5h2.5v6H12V14m0 0za1.5 1.5 0 0 1 1.5 1.5V20a1.5 1.5 0 0 1-1.5 1.5a1.5 1.5 0 0 1-1.5-1.5v-4.5A1.5 1.5 0 0 1 12 14");
}

.ncbein6kj {
  d: path("M6.125 2.5h9.25A2.625 2.625 0 0 1 18 5.125v.75A2.625 2.625 0 0 1 15.375 8.5h-9.25A2.625 2.625 0 0 1 3.5 5.875v-.75A2.625 2.625 0 0 1 6.125 2.5");
}

</style>
