<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="k74vnib1e"/><path class="f1etaqbet"/><path class="u363cab-y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:percentage-score-outline-regular" /></template>
<style>
.f1etaqbet {
  d: path("M15 17a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.k74vnib1e {
  d: path("M3 7a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.u363cab-y {
  d: path("M5 19 19 5");
}

</style>
