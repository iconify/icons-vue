<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="oqn-ez1bm"/><path class="h_i7uu37s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:shuffle-duotone" /></template>
<style>
.h_i7uu37s {
  d: path("M3 18H6C7.5 18 8.9 17.2 9.6 15.9L14.4 8.1C15.1 6.8 16.5 6 18 6H21M18 3L21 6L18 9");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oqn-ez1bm {
  stroke-opacity: 0.4;
  d: path("M3 6H6C7.5 6 8.9 6.8 9.6 8.1L10.2387 9.1379M13.7613 14.8621L14.4 15.9C15.1 17.2 16.5 18 18 18H21M18 15L21 18L18 21");
}

</style>
