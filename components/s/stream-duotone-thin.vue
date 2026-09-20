<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pq8_vobtx"/><path class="nv0ksacrz"/><path class="juj9_pbrn"/><path class="jtrmczbpr"/><path class="n6amu-bmd"/><path class="n_hih6bwb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:stream-duotone-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jtrmczbpr {
  d: path("M2 6h14");
}

.juj9_pbrn {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 18h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.n_hih6bwb {
  d: path("M2 18h14");
}

.n6amu-bmd {
  d: path("M8 12h14");
}

.nv0ksacrz {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 12h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pq8_vobtx {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 6h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
