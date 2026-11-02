<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ozmqjggeo"/><path class="edww9-bza"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:test-tube-duotone" /></template>
<style>
.edww9-bza {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 3v15a3 3 0 0 0 6 0V3M7 3h10m-8 9h6");
}

.ft5dv1b6b {
  fill: none;
}

.ozmqjggeo {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M15 11a1 1 0 0 1 1 1v6a4 4 0 0 1-8 0v-6a1 1 0 0 1 1-1Z");
}

</style>
