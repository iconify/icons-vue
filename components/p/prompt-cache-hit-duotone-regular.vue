<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pr37be5vj"/><path class="gzjf714fp"/><path class="b9po3023a"/><path class="b4x_isbqv"/><path class="d_6ujebpi"/><path class="c5gaambbs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:prompt-cache-hit-duotone-regular" /></template>
<style>
.b4x_isbqv {
  d: path("M8 6H5v12h3");
}

.b9po3023a {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M13.5 9.5 11 12h2.5L11 14.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.c5gaambbs {
  d: path("M13.5 9.5 11 12h2.5L11 14.5");
}

.d_6ujebpi {
  d: path("M16 6h3v12h-3");
}

.gzjf714fp {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M16 6h3v12h-3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pr37be5vj {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 6H5v12h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
