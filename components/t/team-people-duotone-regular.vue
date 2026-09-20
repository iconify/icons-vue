<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="o0u5m7z1w"/><path class="y-n_bmb1w"/><path class="kqlpeub1x"/><path class="tcyp0nbll"/><path class="dd2oi04rr"/><path class="g_eatebwd"/><path class="kx8w1xsla"/><path class="hf-3i5bym"/><path class="jnbv45bnp"/><path class="rkhcgsbdl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:team-people-duotone-regular" /></template>
<style>
.dd2oi04rr {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 19h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.g_eatebwd {
  d: path("M5 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.hf-3i5bym {
  d: path("M15 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.jnbv45bnp {
  d: path("M14 14a3 3 0 0 1 6 0");
}

.kqlpeub1x {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 14a3 3 0 0 1 6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kx8w1xsla {
  d: path("M4 14a3 3 0 0 1 6 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o0u5m7z1w {
  fill: currentColor;
  d: path("M5 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.rkhcgsbdl {
  d: path("M3 19h18");
}

.tcyp0nbll {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M14 14a3 3 0 0 1 6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.y-n_bmb1w {
  fill: currentColor;
  d: path("M15 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
