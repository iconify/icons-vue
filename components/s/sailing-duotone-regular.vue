<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ba23a-bcn"/><path class="mcqabab2o"/><path class="q4tzbe7oa"/><path class="pz8cbl-0n"/><path class="g4vcemb4i"/><path class="k3c7sdb4u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sailing-duotone-regular" /></template>
<style>
.ba23a-bcn {
  fill: currentColor;
  d: path("M12 4v10H2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.g4vcemb4i {
  d: path("M15 8v6h6Z");
}

.k3c7sdb4u {
  d: path("M3 17h18c-1 2 -4 4 -9 4s-8 -2 -9 -4");
}

.mcqabab2o {
  fill: currentColor;
  d: path("M15 8v6h6Z");
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

.pz8cbl-0n {
  d: path("M12 4v10H2Z");
}

.q4tzbe7oa {
  fill: currentColor;
  d: path("M3 17h18c-1 2 -4 4 -9 4s-8 -2 -9 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
