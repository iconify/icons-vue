<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xfs8wlfhn"/><path class="ygr1bbcag"/><path class="opnv9et8e"/><path class="j1iuej2mt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:session-fixation-guard-outline-regular" /></template>
<style>
.j1iuej2mt {
  d: path("m9.5 16 2.5 2.5 2.5 -2.5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.opnv9et8e {
  d: path("M10 14.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.xfs8wlfhn {
  d: path("M5 11.5a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H7a2 2 0 0 1 -2 -2Z");
}

.ygr1bbcag {
  d: path("M8 9.5a4 4 0 0 1 8 0");
}

</style>
