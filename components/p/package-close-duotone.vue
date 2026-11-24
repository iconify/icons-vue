<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="y5xasbcun"/><path class="gt4cznn_q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:package-close-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.gt4cznn_q {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 6c.613-1.226 1.387-2 2-2h10c.613 0 1.387.774 2 2l1 2v10a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2V8zM4 8h16m-10 4l4 4m0-4l-4 4");
}

.y5xasbcun {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M5 6c.326-.651 1.15-1.999 2-2h10c.85.001 1.674 1.349 2 2l1 2H4Z");
}

</style>
