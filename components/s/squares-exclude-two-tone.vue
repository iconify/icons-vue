<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n56bhjtbq"/><path class="ep1zddcya"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:squares-exclude-two-tone" /></template>
<style>
.ep1zddcya {
  d: path("M5 3L13 3C14.1046 3 15 3.8954 15 5L15 8C15 8.5523 15.4477 9 16 9L19 9C20.1046 9 21 9.8954 21 11L21 19C21 20.1046 20.1046 21 19 21L11 21C9.8954 21 9 20.1046 9 19L9 16C9 15.4477 8.5523 15 8 15L5 15C3.8954 15 3 14.1046 3 13L3 5C3 3.8954 3.8954 3 5 3ZM11 9C9.8954 9 9 9.8954 9 11M15 13C15 14.1046 14.1046 15 13 15");
}

.n56bhjtbq {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M9 2L13 2C14.6569 2 16 3.3431 16 5L16 8L19 8C20.6569 8 22 9.3431 22 11L22 19C22 20.6569 20.6569 22 19 22L11 22C9.3431 22 8 20.6569 8 19L8 16L5 16C3.3431 16 2 14.6569 2 13L2 5C2 3.3431 3.3431 2 5 2Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
