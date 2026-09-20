<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="r8lmp2u_n"/><path class="sv2pgmbzl"/><path class="fp0jerb6p"/><path class="tqfrzx00u"/><path class="e8mk-vdvn"/><path class="y5k8b5bfa"/><path class="l517yxbln"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:render-queue-duotone-regular" /></template>
<style>
.e8mk-vdvn {
  d: path("M6 9v6");
}

.fp0jerb6p {
  d: path("M10.5 6H13a3 3 0 0 1 3 3v6a3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3V9a3 3 0 0 1 3 -3h2.5");
}

.l517yxbln {
  d: path("M12 9v6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.r8lmp2u_n {
  fill: currentColor;
  d: path("M10.5 6H13a3 3 0 0 1 3 3v6a3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3V9a3 3 0 0 1 3 -3h2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.sv2pgmbzl {
  fill: currentColor;
  d: path("m19 10 3 -3v10l-3 -3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.tqfrzx00u {
  d: path("m19 10 3 -3v10l-3 -3Z");
}

.y5k8b5bfa {
  d: path("M9 9v6");
}

</style>
