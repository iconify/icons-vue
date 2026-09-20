<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rsea1pbos"/><path class="arfy5knqz"/><path class="ph8xawbhr"/><path class="zuquf0b8s"/><path class="y27nfzbth"/><path class="fcstqn4mf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:nat-gw-duotone-regular" /></template>
<style>
.arfy5knqz {
  fill: currentColor;
  d: path("M9 8a2 2 0 0 1 2 -2h2.5a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H11a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.fcstqn4mf {
  d: path("M18 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ph8xawbhr {
  fill: currentColor;
  d: path("M18 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.rsea1pbos {
  fill: currentColor;
  d: path("M2 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.y27nfzbth {
  d: path("M9 8a2 2 0 0 1 2 -2h2.5a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H11a2 2 0 0 1 -2 -2Z");
}

.zuquf0b8s {
  d: path("M2 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
