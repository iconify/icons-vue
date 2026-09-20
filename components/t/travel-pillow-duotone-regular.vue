<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="t3waa4o9c"/><path class="caiy5fb0x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:travel-pillow-duotone-regular" /></template>
<style>
.caiy5fb0x {
  d: path("M4 10a8 8 0 1 0 16 0 4 4 0 0 1 -4 0 4 4 0 0 0 -8 0 4 4 0 0 1 -4 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.t3waa4o9c {
  fill: currentColor;
  d: path("M4 10a8 8 0 1 0 16 0 4 4 0 0 1 -4 0 4 4 0 0 0 -8 0 4 4 0 0 1 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
