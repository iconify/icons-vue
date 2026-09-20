<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="fvrxg8amo"/><path class="c-wb1qndc"/><path class="pmt07db6r"/><path class="ookop5bym"/><path class="yup53kbpa"/><path class="ia46_gbxj"/><path class="rz_vrfdnw"/><path class="nkk2t23oa"/><path class="nwh20ccjn"/><path class="d12g7vbfa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:property-test-duotone-regular" /></template>
<style>
.c-wb1qndc {
  fill: currentColor;
  d: path("M3 18a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.d12g7vbfa {
  d: path("m13 12 2 2 4 -4");
}

.fvrxg8amo {
  fill: currentColor;
  d: path("M3 6a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ia46_gbxj {
  d: path("M3 6a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.nkk2t23oa {
  d: path("M7.5 6 11 9.5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nwh20ccjn {
  d: path("m7.5 18 3.5 -3.5");
}

.ookop5bym {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m7.5 18 3.5 -3.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pmt07db6r {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7.5 6 11 9.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.rz_vrfdnw {
  d: path("M3 18a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.yup53kbpa {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m13 12 2 2 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
