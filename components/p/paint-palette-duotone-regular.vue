<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="bxvp6ib-c"/><path class="yc_5gkigy"/><path class="dp8rry9sk"/><path class="zid7cdc0n"/><path class="w395fxb3e"/><path class="tcxfk34nj"/><path class="xsyfe-byx"/><path class="ehef6tbzw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:paint-palette-duotone-regular" /></template>
<style>
.bxvp6ib-c {
  fill: currentColor;
  d: path("M12 3a9 9 0 1 0 0 18 2.5 2.5 0 0 0 0 -5 2 2 0 0 1 0 -4h5a4 4 0 0 0 4 -4c0 -3 -4 -5 -9 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.dp8rry9sk {
  fill: currentColor;
  d: path("M6 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ehef6tbzw {
  d: path("M10 17a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tcxfk34nj {
  d: path("M7 8a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.w395fxb3e {
  d: path("M12 3a9 9 0 1 0 0 18 2.5 2.5 0 0 0 0 -5 2 2 0 0 1 0 -4h5a4 4 0 0 0 4 -4c0 -3 -4 -5 -9 -5");
}

.xsyfe-byx {
  d: path("M6 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.yc_5gkigy {
  fill: currentColor;
  d: path("M7 8a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.zid7cdc0n {
  fill: currentColor;
  d: path("M10 17a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
