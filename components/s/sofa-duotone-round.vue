<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="pry1i1b6m"/><path class="ojknjol7p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:sofa-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ojknjol7p {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 11v2a4 4 0 0 0 4 4h10a4 4 0 0 0 4-4v-2a2 2 0 1 0-4 0a2 2 0 0 1-2 2H9a2 2 0 0 1-2-2a2 2 0 1 0-4 0m2 6v2m14-2v2M12 5v8M5 9a4 4 0 0 1 4-4h6a4 4 0 0 1 4 4");
}

.pry1i1b6m {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M3 11a2 2 0 1 1 4 0a2 2 0 0 0 2 2h6a2 2 0 0 0 2-2a2 2 0 1 1 4 0v2a4 4 0 0 1-4 4H7a4 4 0 0 1-4-4Z");
}

</style>
