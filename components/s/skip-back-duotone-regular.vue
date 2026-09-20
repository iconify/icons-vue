<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nk6qfwujr"/><path class="ay0-xnb_u"/><path class="e80on1hgs"/><path class="azgrucbqu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:skip-back-duotone-regular" /></template>
<style>
.ay0-xnb_u {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 5v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.azgrucbqu {
  d: path("M7 5v14");
}

.e80on1hgs {
  d: path("m18 5 -7 7 7 7");
}

.nk6qfwujr {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m18 5 -7 7 7 7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
