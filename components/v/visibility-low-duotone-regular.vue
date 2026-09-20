<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="dktry7bqc"/><path class="pfxru8alb"/><path class="r81yrrbur"/><path class="kf31o4j9n"/><path class="m6ifjboxi"/><path class="rp243mbkd"/><path class="bo51iypxr"/><path class="piohzog1p"/><path class="irm-6r_xs"/><path class="ffs26fbkv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:visibility-low-duotone-regular" /></template>
<style>
.bo51iypxr {
  d: path("M10 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.dktry7bqc {
  fill: currentColor;
  d: path("M10 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ffs26fbkv {
  d: path("M12 17v4");
}

.irm-6r_xs {
  d: path("M3 17v4");
}

.kf31o4j9n {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 17v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.m6ifjboxi {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 17v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pfxru8alb {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6.36 9.95a6 6 0 0 1 11.28 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.piohzog1p {
  d: path("M3 19h9");
}

.r81yrrbur {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 19h9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.rp243mbkd {
  d: path("M6.36 9.95a6 6 0 0 1 11.28 0");
}

</style>
