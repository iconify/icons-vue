<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="keqc2pbxm"/><path class="aff9hemvj"/><path class="q686vz2zk"/><path class="svx7-715v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:wildlife-outline-regular" /></template>
<style>
.aff9hemvj {
  d: path("M9 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.keqc2pbxm {
  d: path("M4 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.q686vz2zk {
  d: path("M14 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.svx7-715v {
  d: path("M6 17a5.5 5.5 0 0 1 11 0 4.5 4.5 0 0 1 -5.5 4A4.5 4.5 0 0 1 6 17");
}

</style>
