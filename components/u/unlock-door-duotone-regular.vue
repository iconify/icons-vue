<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ngcuq3bxa"/><path class="kwcqu2u9a"/><path class="ef-jgqbdk"/><path class="k4p4tzbhq"/><path class="kvmhsdkct"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:unlock-door-duotone-regular" /></template>
<style>
.ef-jgqbdk {
  d: path("M4 3v18h10V3Z");
}

.k4p4tzbhq {
  d: path("M17 13v6h5v-6Z");
}

.kvmhsdkct {
  d: path("M18 13v-3c0 -1.5 1 -2.5 2 -2.5s1.5 1 1.5 2.5");
}

.kwcqu2u9a {
  fill: currentColor;
  d: path("M17 13v6h5v-6Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ngcuq3bxa {
  fill: currentColor;
  d: path("M4 3v18h10V3Z");
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

</style>
