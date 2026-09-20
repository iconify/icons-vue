<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="c4my-jbpv"/><path class="eqfz7ub4f"/><path class="w1omirbkc"/><path class="nqnw98byf"/><path class="pjklsjpyn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:top-result-outline-regular" /></template>
<style>
.c4my-jbpv {
  d: path("M2 5a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.eqfz7ub4f {
  d: path("M5 6.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.nqnw98byf {
  d: path("M2 14h20");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pjklsjpyn {
  d: path("M4 18h12");
}

.w1omirbkc {
  d: path("M9 6.5h9");
}

</style>
