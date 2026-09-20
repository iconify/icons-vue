<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="is1j44btv"/><path class="e65_6jbte"/><path class="n9baun0jc"/><path class="g4flvub6o"/><path class="oqj-o0b2r"/><path class="ljx4iubuw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:schema-registry-duotone-regular" /></template>
<style>
.e65_6jbte {
  d: path("M2 7a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.g4flvub6o {
  d: path("M4 6V2.5h6L13.5 6");
}

.is1j44btv {
  fill: currentColor;
  d: path("M2 7a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ljx4iubuw {
  d: path("M5 18h10");
}

.n9baun0jc {
  d: path("M2 10h20");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oqj-o0b2r {
  d: path("M5 14h14");
}

</style>
