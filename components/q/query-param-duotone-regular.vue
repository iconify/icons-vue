<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wno2bb6wt"/><path class="wywiukbgn"/><path class="ku_telleq"/><path class="ip4g20bxl"/><path class="ldodvk1_f"/><path class="d6cu3qpew"/><path class="m8y64tbqv"/><path class="vqi6vft7m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:query-param-duotone-regular" /></template>
<style>
.d6cu3qpew {
  d: path("M17 3h4v18h-4");
}

.ip4g20bxl {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9.5 10.5A2.5 2.5 0 1 1 12 13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ku_telleq {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M17 3h4v18h-4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ldodvk1_f {
  d: path("M7 3H3v18h4");
}

.m8y64tbqv {
  d: path("M9.5 10.5A2.5 2.5 0 1 1 12 13");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vqi6vft7m {
  d: path("M11 15.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.wno2bb6wt {
  fill: currentColor;
  d: path("M11 15.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.wywiukbgn {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 3H3v18h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
