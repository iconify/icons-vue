<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rnnki-bvy"/><path class="k6nj2fbya"/><path class="i1jp0gbac"/><path class="emoyz4b2o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:secure-delete-outline-regular" /></template>
<style>
.emoyz4b2o {
  d: path("m15 11 -6 6");
}

.i1jp0gbac {
  d: path("m9 11 6 6");
}

.k6nj2fbya {
  d: path("M3 5h18");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rnnki-bvy {
  d: path("M6 10a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H8a2 2 0 0 1 -2 -2Z");
}

</style>
