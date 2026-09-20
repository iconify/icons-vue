<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="e0ns0_bco"/><path class="vyfu-5bfh"/><path class="cqx_5fa1v"/><path class="y18a3dbyh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:vector-duotone-regular" /></template>
<style>
.cqx_5fa1v {
  d: path("M3 21 20 4");
}

.e0ns0_bco {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 21 20 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vyfu-5bfh {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M13 4h7v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.y18a3dbyh {
  d: path("M13 4h7v7");
}

</style>
