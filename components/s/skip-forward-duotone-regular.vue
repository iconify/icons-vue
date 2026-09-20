<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pu-ddejww"/><path class="ocgq8oo_l"/><path class="swmt31b1p"/><path class="gtsw5xviq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:skip-forward-duotone-regular" /></template>
<style>
.gtsw5xviq {
  d: path("M17 5v14");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ocgq8oo_l {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M17 5v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pu-ddejww {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m6 5 7 7 -7 7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.swmt31b1p {
  d: path("m6 5 7 7 -7 7");
}

</style>
