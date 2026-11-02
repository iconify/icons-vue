<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ek1jm9b6y"/><path class="nbqbr9b0g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:notion-duocolor-round" /></template>
<style>
.ek1jm9b6y {
  stroke-opacity: 0.4;
  d: path("M3 3h15l3 3v15H6l-3-3Zm18 3H6v15M3 3l3 3");
}

.nbqbr9b0g {
  d: path("M11 17v-7l5 7v-7");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
