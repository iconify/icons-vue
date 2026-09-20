<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jfvoq9bhn"/><path class="zdgvfxbbv"/><path class="slz7u0oyn"/><path class="uea_ybysx"/><path class="it83nbbll"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:slowly-changing-dimension-outline-regular" /></template>
<style>
.it83nbbll {
  d: path("M5 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.jfvoq9bhn {
  d: path("M2 4.5A2.5 2.5 0 0 1 4.5 2h15A2.5 2.5 0 0 1 22 4.5 2.5 2.5 0 0 1 19.5 7h-15A2.5 2.5 0 0 1 2 4.5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.slz7u0oyn {
  d: path("M2 19.5A2.5 2.5 0 0 1 4.5 17h15a2.5 2.5 0 0 1 2.5 2.5 2.5 2.5 0 0 1 -2.5 2.5h-15A2.5 2.5 0 0 1 2 19.5");
}

.uea_ybysx {
  d: path("M5 4.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.zdgvfxbbv {
  d: path("M2 12a2.5 2.5 0 0 1 2.5 -2.5h15A2.5 2.5 0 0 1 22 12a2.5 2.5 0 0 1 -2.5 2.5h-15A2.5 2.5 0 0 1 2 12");
}

</style>
