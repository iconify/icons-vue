<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="kag6yacuj"/><path class="oda0k3bdy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:piggy-bank-duocolor" /></template>
<style>
.kag6yacuj {
  stroke-opacity: 0.4;
  d: path("M7 5a2 2 0 1 0 4 0a2 2 0 0 0-4 0m1 14v2m6-2v2");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oda0k3bdy {
  d: path("M11 11h4a3 3 0 0 1 3 3v2a3 3 0 0 1-3 3H8a4 4 0 1 1 0-8zm2 0l3-3v3Zm5 2h1a1 1 0 0 1 1 1v2a1 1 0 0 1-1 1h-1zm-3 1h.01");
}

</style>
