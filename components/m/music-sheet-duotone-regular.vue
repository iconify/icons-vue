<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mzsthfbrb"/><path class="xlm4t5bbx"/><path class="nzpsuduik"/><path class="f8gsx7b5s"/><path class="vslz5yb3q"/><path class="rynjb5q0q"/><path class="h33iclbph"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:music-sheet-duotone-regular" /></template>
<style>
.f8gsx7b5s {
  d: path("M6 8h12");
}

.h33iclbph {
  d: path("M11 16V9");
}

.mzsthfbrb {
  fill: currentColor;
  d: path("M3 5a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
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

.nzpsuduik {
  d: path("M3 5a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

.rynjb5q0q {
  d: path("M7 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.vslz5yb3q {
  d: path("M6 12h12");
}

.xlm4t5bbx {
  fill: currentColor;
  d: path("M7 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
