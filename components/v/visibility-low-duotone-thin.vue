<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dktry7bqc"/><path class="jw01oqbhb"/><path class="dhondqbyc"/><path class="scq6fxlrr"/><path class="sx1m0u7ew"/><path class="rp243mbkd"/><path class="bo51iypxr"/><path class="piohzog1p"/><path class="irm-6r_xs"/><path class="ffs26fbkv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:visibility-low-duotone-thin" /></template>
<style>
.bo51iypxr {
  d: path("M10 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.dhondqbyc {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 19h9");
  opacity: var(--svg-opacity--0-2, 0.2);
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

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.irm-6r_xs {
  d: path("M3 17v4");
}

.jw01oqbhb {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6.36 9.95a6 6 0 0 1 11.28 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.piohzog1p {
  d: path("M3 19h9");
}

.rp243mbkd {
  d: path("M6.36 9.95a6 6 0 0 1 11.28 0");
}

.scq6fxlrr {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 17v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.sx1m0u7ew {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 17v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
