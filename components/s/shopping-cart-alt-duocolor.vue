<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="fqkx16gqv"/><path class="r4opveb8e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shopping-cart-alt-duocolor" /></template>
<style>
.fqkx16gqv {
  stroke-opacity: 0.4;
  d: path("M8 18a2 2 0 1 0 4 0a2 2 0 0 0-4 0m8 0a2 2 0 1 0 4 0a2 2 0 0 0-4 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.r4opveb8e {
  d: path("M3 4h1c.415 0 .822.406 1 1l3 10c.178.594.991 1 2 1h8M6 7h13c.82 0 1.328 1.016 1 2l-1 3c-.2.597-.602 1-1 1H8");
}

</style>
