<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rpia5zilk"/><path class="fw9f_lb8d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:sliders-horizontal-duotone" /></template>
<style>
.fw9f_lb8d {
  d: path("M16 3L16 7M10 10L10 14M14 17L14 21");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rpia5zilk {
  stroke-opacity: 0.4;
  d: path("M3 5L12 5M21 5L16 5M3 12L10 12M21 12L14 12M3 19L10 19M21 19L14 19");
}

</style>
