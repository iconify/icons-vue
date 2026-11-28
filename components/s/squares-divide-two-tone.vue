<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nsuu1xbaa"/><path class="xo36h9_kq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:squares-divide-two-tone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nsuu1xbaa {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8 16L5 16C3.3431 16 2 14.6569 2 13L2 5C2 3.3431 3.3431 2 5 2L9 2L13 2C14.6569 2 16 3.3431 16 5L16 8L19 8C20.6569 8 22 9.3431 22 11L22 19C22 20.6569 20.6569 22 19 22L11 22C9.3431 22 8 20.6569 8 19Z");
  stroke: none;
}

.xo36h9_kq {
  d: path("M5 3L13 3C14.1046 3 15 3.8954 15 5L15 13C15 14.1046 14.1046 15 13 15L5 15C3.8954 15 3 14.1046 3 13L3 5C3 3.8954 3.8954 3 5 3ZM11 9L19 9C20.1046 9 21 9.8954 21 11L21 19C21 20.1046 20.1046 21 19 21L11 21C9.8954 21 9 20.1046 9 19L9 11C9 9.8954 9.8954 9 11 9Z");
}

</style>
