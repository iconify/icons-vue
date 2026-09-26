<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="yypun9-bb"/><path class="yspugcb-m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:skip-forward-two-tone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.yspugcb-m {
  d: path("M5 7.0059C5 5.271102 7.057553 4.358975 8.343026 5.523914L14.671513 11.259007C15.109496 11.655922 15.109496 12.344078 14.671513 12.740993L8.343026 18.476086C7.057553 19.641025 5 18.728898 5 16.9941ZM19 5V19");
}

.yypun9-bb {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 7.0059C4 4.403702 7.08633 3.035512 9.014539 4.782922L15.343026 10.518015C16.218991 11.311844 16.218991 12.688156 15.343026 13.481985L9.014539 19.217078C7.08633 20.964488 4 19.596298 4 16.9941Z");
  stroke: none;
}

</style>
