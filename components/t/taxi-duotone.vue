<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="q14kf2bgl"/><path class="wlym12bam"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:taxi-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.q14kf2bgl {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M16 18H8v2H6v-2a2 2 0 0 1-2-2v-4l1-2c.326-.651 1.15-1.999 2-2h10c.85.001 1.674 1.349 2 2l1 2v4a2 2 0 0 1-2 2v2h-2Z");
}

.wlym12bam {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 5h4M8 15h.01M16 15h.01M12 18H6a2 2 0 0 1-2-2v-4l1-2c.613-1.226 1.387-2 2-2h10c.613 0 1.387.774 2 2l1 2v4a2 2 0 0 1-2 2zm-6 0h2v2H6Zm10 0h2v2h-2ZM3 12h18");
}

</style>
