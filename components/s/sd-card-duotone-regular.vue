<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ycprquf3q"/><path class="ut22q-b2l"/><path class="qx4fzbhlz"/><path class="ah0cuqn_g"/><path class="q534om6ef"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sd-card-duotone-regular" /></template>
<style>
.ah0cuqn_g {
  d: path("M11 5v4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.q534om6ef {
  d: path("M14 8v4");
}

.qx4fzbhlz {
  d: path("M8 5v4");
}

.ut22q-b2l {
  d: path("M4 2h11l5 5v15H4Z");
}

.ycprquf3q {
  fill: currentColor;
  d: path("M4 2h11l5 5v15H4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
