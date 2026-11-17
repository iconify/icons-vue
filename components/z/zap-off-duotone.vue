<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ujezbcbol"/><path class="te0gjfbbc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:zap-off-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.te0gjfbbc {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m7.658 10.658l-2.035 2.56A.482.482 0 0 0 6 14h3.25a1 1 0 0 1 1 1v5c0 .33.417.476.623.217l2.81-3.533m2.659-3.342l2.035-2.56A.482.482 0 0 0 18 10h-3.25a1 1 0 0 1-1-1V4a.35.35 0 0 0-.623-.217l-2.81 3.533M2 5l17 17");
}

.ujezbcbol {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m16.342 13.342l-6.026-6.026l2.811-3.533A.349.349 0 0 1 13.75 4v5a1 1 0 0 0 1 1H18a.481.481 0 0 1 .377.783Zm-5.469 6.875A.349.349 0 0 1 10.25 20v-5a1 1 0 0 0-1-1H6a.481.481 0 0 1-.377-.783l2.035-2.559l6.026 6.026Z");
}

</style>
