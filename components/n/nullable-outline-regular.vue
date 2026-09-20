<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hpthd_boc"/><path class="velnaj6mf"/><path class="epou1mbuy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:nullable-outline-regular" /></template>
<style>
.epou1mbuy {
  d: path("M11 16a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.hpthd_boc {
  d: path("M4 6a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.velnaj6mf {
  d: path("M9.5 10a2.5 2.5 0 1 1 2.5 2.5");
}

</style>
