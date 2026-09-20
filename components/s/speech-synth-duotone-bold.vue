<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="gc082hhxv"/><path class="yze2sl0ax"/><path class="yrlnsyb8l"/><path class="st3656inm"/><path class="wt9oil39f"/><path class="ni7913pru"/><path class="mu-p7sbhe"/><path class="qm17m3bad"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:speech-synth-duotone-bold" /></template>
<style>
.gc082hhxv {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 10h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mu-p7sbhe {
  d: path("M16.12 9.88a3 3 0 0 1 0 4.24");
}

.ni7913pru {
  d: path("M3 14h5");
}

.qm17m3bad {
  d: path("M18.95 7.05a7 7 0 0 1 0 9.9");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.st3656inm {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M18.95 7.05a7 7 0 0 1 0 9.9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wt9oil39f {
  d: path("M3 10h5");
}

.yrlnsyb8l {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M16.12 9.88a3 3 0 0 1 0 4.24");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.yze2sl0ax {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 14h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
