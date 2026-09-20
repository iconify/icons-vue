<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="bc-pkhdhv"/><path class="jy5r5qbju"/><path class="zu4ajq05m"/><path class="eqqc-z5sv"/><path class="q88myjbfp"/><path class="va4lqxm9h"/><path class="fqg-d6bob"/><path class="plef9ibei"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:region-pair-duotone-regular" /></template>
<style>
.bc-pkhdhv {
  fill: currentColor;
  d: path("M2.5 6.5a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.eqqc-z5sv {
  d: path("M3 6.5h7");
}

.fqg-d6bob {
  d: path("M14 17.5h7");
}

.jy5r5qbju {
  fill: currentColor;
  d: path("M13.5 17.5a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.plef9ibei {
  d: path("M17.5 14v7");
}

.q88myjbfp {
  d: path("M6.5 3v7");
}

.va4lqxm9h {
  d: path("M13.5 17.5a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

.zu4ajq05m {
  d: path("M2.5 6.5a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

</style>
