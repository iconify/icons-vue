<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="talu39b-j"/><path class="o_j2p0j7o"/><path class="cgqalac9z"/><path class="v-m1aobza"/><path class="e0ead5bmw"/><path class="pf-zwj5ei"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:nudge-duotone-regular" /></template>
<style>
.cgqalac9z {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m6 10 2 2 -2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.e0ead5bmw {
  d: path("M3 12h3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o_j2p0j7o {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 12h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pf-zwj5ei {
  d: path("m6 10 2 2 -2 2");
}

.talu39b-j {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M16.32 7a5.5 5.5 0 1 1 -4.64 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.v-m1aobza {
  d: path("M16.32 7a5.5 5.5 0 1 1 -4.64 0");
}

</style>
