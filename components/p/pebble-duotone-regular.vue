<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="g4-0p1n1h"/><path class="j8hnr9b3j"/><path class="iqp9rd4vv"/><path class="pj9q08bqv"/><path class="vtk0-_bov"/><path class="pe31e6bgt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:pebble-duotone-regular" /></template>
<style>
.g4-0p1n1h {
  fill: currentColor;
  d: path("M3 9a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.iqp9rd4vv {
  fill: currentColor;
  d: path("M7.5 17a4.5 4.5 0 1 0 9 0 4.5 4.5 0 1 0 -9 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.j8hnr9b3j {
  fill: currentColor;
  d: path("M12.5 8a3.5 3.5 0 1 0 7 0 3.5 3.5 0 1 0 -7 0");
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

.pe31e6bgt {
  d: path("M7.5 17a4.5 4.5 0 1 0 9 0 4.5 4.5 0 1 0 -9 0");
}

.pj9q08bqv {
  d: path("M3 9a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

.vtk0-_bov {
  d: path("M12.5 8a3.5 3.5 0 1 0 7 0 3.5 3.5 0 1 0 -7 0");
}

</style>
