<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rsea1pbos"/><path class="qshyiibwt"/><path class="zuquf0b8s"/><path class="lxjzt-y8t"/><path class="fc2t2rsyg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:token-in-duotone-regular" /></template>
<style>
.fc2t2rsyg {
  d: path("M13 7a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2h-4a2 2 0 0 1 -2 -2Z");
}

.lxjzt-y8t {
  d: path("M7.5 9.5 10 12l-2.5 2.5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qshyiibwt {
  fill: currentColor;
  d: path("M13 7a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2h-4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.rsea1pbos {
  fill: currentColor;
  d: path("M2 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.zuquf0b8s {
  d: path("M2 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
