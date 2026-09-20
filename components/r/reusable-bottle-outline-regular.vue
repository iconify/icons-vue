<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="le629bcat"/><path class="n953y9b3y"/><path class="l0v-b4kbr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:reusable-bottle-outline-regular" /></template>
<style>
.l0v-b4kbr {
  d: path("M8 12h8");
}

.le629bcat {
  d: path("M8 7v14h8V7Z");
}

.n953y9b3y {
  d: path("M10 7V3h4v4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
