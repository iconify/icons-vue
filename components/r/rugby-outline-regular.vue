<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="epka50bri"/><path class="f2vh026ub"/><path class="y0y0ccsoe"/><path class="fkf_gcbra"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:rugby-outline-regular" /></template>
<style>
.epka50bri {
  d: path("M3 12c3 -4 6 -7 9 -7s6 3 9 7c-3 4 -6 7 -9 7s-6 -3 -9 -7");
}

.f2vh026ub {
  d: path("M10 9h4");
}

.fkf_gcbra {
  d: path("M10 15h4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.y0y0ccsoe {
  d: path("M10 12h4");
}

</style>
