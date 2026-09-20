<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hemk1tbpo"/><path class="da76adb-h"/><path class="g4lz7ob4p"/><path class="zobhtyb0t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:storage-outline-regular" /></template>
<style>
.da76adb-h {
  d: path("M5 7.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.g4lz7ob4p {
  d: path("M2 16a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.hemk1tbpo {
  d: path("M2 6a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.zobhtyb0t {
  d: path("M5 17.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
