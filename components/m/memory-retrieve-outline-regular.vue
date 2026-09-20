<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n0n63pb2v"/><path class="dhoelsbfc"/><path class="atvcffgcu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:memory-retrieve-outline-regular" /></template>
<style>
.atvcffgcu {
  d: path("m11.5 8 3.5 3.5");
}

.dhoelsbfc {
  d: path("M9 7.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.n0n63pb2v {
  d: path("M4 15v4h16v-4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
