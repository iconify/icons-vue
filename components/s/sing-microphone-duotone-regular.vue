<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="thtmxj09n"/><path class="suyg0ubax"/><path class="dam2g8x5x"/><path class="ffs26fbkv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sing-microphone-duotone-regular" /></template>
<style>
.dam2g8x5x {
  d: path("M6 11a6 6 0 0 0 12 0");
}

.ffs26fbkv {
  d: path("M12 17v4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.suyg0ubax {
  d: path("M12 3a3 3 0 0 1 3 3v5a3 3 0 0 1 -6 0V6a3 3 0 0 1 3 -3");
}

.thtmxj09n {
  fill: currentColor;
  d: path("M12 3a3 3 0 0 1 3 3v5a3 3 0 0 1 -6 0V6a3 3 0 0 1 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
