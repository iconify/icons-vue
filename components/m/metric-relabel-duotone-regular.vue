<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="v72ku2b4z"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="gffdk79ec"/><path class="wb770htsg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:metric-relabel-duotone-regular" /></template>
<style>
.gffdk79ec {
  d: path("M9 8h3l3 3 -3 3H9Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oifr9zbpt {
  d: path("M4 20h16");
}

.r3faxubne {
  d: path("M4 4v16");
}

.v72ku2b4z {
  fill: currentColor;
  d: path("M9 8h3l3 3 -3 3H9Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.wb770htsg {
  d: path("m8.5 14.5 7 -7");
}

</style>
