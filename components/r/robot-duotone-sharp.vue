<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="s6nn5sl6y"/><path class="umx22sbov"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:robot-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.s6nn5sl6y {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M12 5a1 1 0 1 1 0-2a1 1 0 0 1 0 2m7 16H5V9h14Z");
}

.umx22sbov {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 9h14v12H5Zm7 0V5m-1-1a1 1 0 1 0 2 0a1 1 0 0 0-2 0M5 15H3m16 0h2M9 13v2m6-2v2");
}

</style>
