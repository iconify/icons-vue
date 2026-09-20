<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="o7k-2fb3i"/><path class="q0c4v9qfz"/><path class="gq9v58bnx"/><path class="pdl4ijbea"/><path class="ic718vbfc"/><path class="n4avueb2x"/><path class="xxhou8bla"/><path class="u-hehrbeq"/><path class="tum88bbiw"/><path class="t407nkbfi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:strength-duotone-regular" /></template>
<style>
.gq9v58bnx {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M10 17h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ic718vbfc {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m9 7 3 -3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.n4avueb2x {
  d: path("M6 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o7k-2fb3i {
  fill: currentColor;
  d: path("M6 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.pdl4ijbea {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 12V4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.q0c4v9qfz {
  fill: currentColor;
  d: path("M14 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.t407nkbfi {
  d: path("m9 7 3 -3 3 3");
}

.tum88bbiw {
  d: path("M12 12V4");
}

.u-hehrbeq {
  d: path("M10 17h4");
}

.xxhou8bla {
  d: path("M14 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
