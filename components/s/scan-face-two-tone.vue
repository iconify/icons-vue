<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="s-_3y1_8e"/><path class="jj85k7ctk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:scan-face-two-tone" /></template>
<style>
.jj85k7ctk {
  d: path("M9 10L9 11M15 10L15 11M9 15C10 16 11 16.5 12 16.5C13 16.5 14 16 15 15");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.s-_3y1_8e {
  stroke-opacity: 0.4;
  d: path("M3 8L3 6C3 4.3431 4.3431 3 6 3L8 3M16 3L18 3C19.6569 3 21 4.3431 21 6L21 8M21 16L21 18C21 19.6569 19.6569 21 18 21L16 21M8 21L6 21C4.3431 21 3 19.6569 3 18L3 16");
}

</style>
