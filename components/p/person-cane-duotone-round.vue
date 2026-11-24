<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ox8bmnvug"/><path class="vad5ubbvf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:person-cane-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ox8bmnvug {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M7 4a1 1 0 1 1 2 0a1 1 0 0 1-2 0");
}

.vad5ubbvf {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 4a1 1 0 1 0 2 0a1 1 0 0 0-2 0m1 4v6m-3 7l3-7l3 7M8 9l5 3m0 0l6 9");
}

</style>
