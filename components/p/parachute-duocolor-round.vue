<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ayzshzbep"/><path class="astx6kbnz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:parachute-duocolor-round" /></template>
<style>
.astx6kbnz {
  d: path("M3 9c0-4 4-6 9-6s9 2 9 6q-4.5-3-9 0q-4.5-3-9 0");
}

.ayzshzbep {
  stroke-opacity: 0.4;
  d: path("m3 9l9 9l9-9m-9 0v12m-3 0h6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
