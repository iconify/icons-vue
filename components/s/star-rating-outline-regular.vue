<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hufxdfd1k"/><path class="x7bkced7s"/><path class="nesq7qlnx"/><path class="u4sowhi7h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:star-rating-outline-regular" /></template>
<style>
.hufxdfd1k {
  d: path("m6.5 8 2 2 -2 2 -2 -2Z");
}

.nesq7qlnx {
  d: path("m17.5 8 2 2 -2 2 -2 -2Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.u4sowhi7h {
  d: path("M4 16h16");
}

.x7bkced7s {
  d: path("m12 8 2 2 -2 2 -2 -2Z");
}

</style>
