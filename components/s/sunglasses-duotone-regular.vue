<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="c9e-6nb7q"/><path class="op8wvfbgm"/><path class="tc3rjukod"/><path class="ac4p_wikp"/><path class="f2vh026ub"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sunglasses-duotone-regular" /></template>
<style>
.ac4p_wikp {
  d: path("M14 9h7v5a3.5 3.5 0 0 1 -7 0Z");
}

.c9e-6nb7q {
  fill: currentColor;
  d: path("M3 9h7v5a3.5 3.5 0 0 1 -7 0Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.f2vh026ub {
  d: path("M10 9h4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.op8wvfbgm {
  fill: currentColor;
  d: path("M14 9h7v5a3.5 3.5 0 0 1 -7 0Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.tc3rjukod {
  d: path("M3 9h7v5a3.5 3.5 0 0 1 -7 0Z");
}

</style>
