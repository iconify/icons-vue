<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="crgm97xoy"/><path class="k4qo1xe9v"/><path class="x4bmljlar"/><path class="wtfq6b2ta"/><path class="ui32hib9b"/><path class="htavkzbpk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:shuttle-bus-outline-regular" /></template>
<style>
.crgm97xoy {
  d: path("M4 4a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

.htavkzbpk {
  d: path("m17 18 2 2 -2 2");
}

.k4qo1xe9v {
  d: path("M4 6h16");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ui32hib9b {
  d: path("M5 20h14");
}

.wtfq6b2ta {
  d: path("M14 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.x4bmljlar {
  d: path("M6 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
