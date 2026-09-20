<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n5m_-dbxl"/><path class="ru4yg4kdx"/><path class="z50cotl-z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:renewable-energy-duotone-regular" /></template>
<style>
.n5m_-dbxl {
  fill: currentColor;
  d: path("M4 20c0 -9.6 6.4 -16 16 -16 0 9.6 -6.4 16 -16 16");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ru4yg4kdx {
  d: path("M4 20c0 -9.6 6.4 -16 16 -16 0 9.6 -6.4 16 -16 16");
}

.z50cotl-z {
  d: path("m13 8 -3.5 3.5h3L9 15");
}

</style>
