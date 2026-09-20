<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="cojfndboq"/><path class="nm0sjob8b"/><path class="mwtwrccyv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:medical-thermometer-duotone-regular" /></template>
<style>
.cojfndboq {
  fill: currentColor;
  d: path("M7 19a2.5 2.5 0 0 1 0 -5l9 -9a2.5 2.5 0 0 1 3 3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.mwtwrccyv {
  d: path("m10 15 5 -5");
}

.nm0sjob8b {
  d: path("M7 19a2.5 2.5 0 0 1 0 -5l9 -9a2.5 2.5 0 0 1 3 3Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
