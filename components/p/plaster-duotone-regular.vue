<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tavwlyoaj"/><path class="e04igbcxt"/><path class="pme-z0buy"/><path class="de23ghs-u"/><path class="p-3tqnbzb"/><path class="qrqlpabxp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:plaster-duotone-regular" /></template>
<style>
.de23ghs-u {
  d: path("m3.5 15.5 12 -12a4 4 0 0 1 5 5l-12 12a4 4 0 0 1 -5 -5");
}

.e04igbcxt {
  fill: currentColor;
  d: path("M9 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
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

.p-3tqnbzb {
  d: path("M9 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.pme-z0buy {
  fill: currentColor;
  d: path("M13 10a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.qrqlpabxp {
  d: path("M13 10a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.tavwlyoaj {
  fill: currentColor;
  d: path("m3.5 15.5 12 -12a4 4 0 0 1 5 5l-12 12a4 4 0 0 1 -5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
