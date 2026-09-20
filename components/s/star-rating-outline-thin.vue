<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hufxdfd1k"/><path class="x7bkced7s"/><path class="nesq7qlnx"/><path class="u4sowhi7h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:star-rating-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hufxdfd1k {
  d: path("m6.5 8 2 2 -2 2 -2 -2Z");
}

.nesq7qlnx {
  d: path("m17.5 8 2 2 -2 2 -2 -2Z");
}

.u4sowhi7h {
  d: path("M4 16h16");
}

.x7bkced7s {
  d: path("m12 8 2 2 -2 2 -2 -2Z");
}

</style>
