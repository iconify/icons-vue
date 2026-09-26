<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="kt5437z2p"/><path class="wzyb8kbbs"/><path class="p-c4zi3wv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:table-rows-add-below-duotone" /></template>
<style>
.kt5437z2p {
  stroke-opacity: 0.4;
  d: path("M5 19.8284C3.8014 19.4046 3 18.2713 3 17L3 11M21 11L21 17C21 18.2713 20.1986 19.4046 19 19.8284");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p-c4zi3wv {
  d: path("M12 16L12 22M9 19L15 19");
}

.wzyb8kbbs {
  fill: currentColor;
  d: path("M2 12L22 12L22 5C22 2.7909 20.2091 1 18 1L6 1C3.7909 1 2 2.7909 2 5L2 12Z");
  stroke: none;
}

</style>
