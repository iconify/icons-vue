<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="eba0prbjj"/><path class="petm7cbey"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:ruler-duocolor-sharp" /></template>
<style>
.eba0prbjj {
  stroke-opacity: 0.4;
  d: path("m5 13l2 2m2-6l2 2m2-6l2 2");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.petm7cbey {
  d: path("m9 9l6-6l6 6L9 21l-6-6z");
}

</style>
