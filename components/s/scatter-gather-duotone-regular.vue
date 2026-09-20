<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rsea1pbos"/><path class="ph8xawbhr"/><path class="i-z3r4bfm"/><path class="laixe5spi"/><path class="zuquf0b8s"/><path class="fcstqn4mf"/><path class="b7emas-0s"/><path class="qgv_f1esc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:scatter-gather-duotone-regular" /></template>
<style>
.b7emas-0s {
  d: path("M5.5 10.5 10 6h4l4.5 4.5");
}

.fcstqn4mf {
  d: path("M18 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.i-z3r4bfm {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5.5 10.5 10 6h4l4.5 4.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.laixe5spi {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5.5 13.5 10 18h4l4.5 -4.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ph8xawbhr {
  fill: currentColor;
  d: path("M18 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.qgv_f1esc {
  d: path("M5.5 13.5 10 18h4l4.5 -4.5");
}

.rsea1pbos {
  fill: currentColor;
  d: path("M2 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.zuquf0b8s {
  d: path("M2 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
