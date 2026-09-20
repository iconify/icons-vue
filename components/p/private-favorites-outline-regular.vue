<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="a3b7rvb1p"/><path class="ltriwmbuu"/><path class="u0hfy7bsd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:private-favorites-outline-regular" /></template>
<style>
.a3b7rvb1p {
  d: path("M5 12a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2v7a2 2 0 0 1 -2 2H7a2 2 0 0 1 -2 -2Z");
}

.ltriwmbuu {
  d: path("M8 10a4 4 0 0 1 8 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.u0hfy7bsd {
  d: path("M9 14a1.5 1.5 0 0 1 3 0 1.5 1.5 0 0 1 3 0l-3 3Z");
}

</style>
