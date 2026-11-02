<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ouhcolk2v"/><path class="bc1s6rx7l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shopping-cart-duocolor-sharp" /></template>
<style>
.bc1s6rx7l {
  d: path("M3 4h2l3 12h11l2-8H6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ouhcolk2v {
  stroke-opacity: 0.4;
  d: path("M8 20a1 1 0 1 0 2 0a1 1 0 0 0-2 0m9 0a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

</style>
