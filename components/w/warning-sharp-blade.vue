<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="q7ywadcny"/><path class="wc1pm8b5h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:warning-sharp-blade" /></template>
<style>
.q7ywadcny {
  d: path("m12 2.5l9.5 18h-19Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wc1pm8b5h {
  d: path("M10.5 18v-7.5c2.5 1.75 3.25 4 3.25 7.5Z");
}

</style>
