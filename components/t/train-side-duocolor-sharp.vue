<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ut1zoqbwr"/><path class="g5bk4d_ug"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:train-side-duocolor-sharp" /></template>
<style>
.g5bk4d_ug {
  d: path("M19 15H3V5h8a10 10 0 0 1 8 4c1.2 1.6 2 2.5 2 4a2 2 0 0 1-2 2M3 9h16M9 5v4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ut1zoqbwr {
  stroke-opacity: 0.4;
  d: path("M3 19h18");
}

</style>
