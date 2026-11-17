<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="w9ewxlbfh"/><path class="ul283zbdu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:sprinkler-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ul283zbdu {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 13a2 2 0 1 0 4 0a2 2 0 0 0-4 0m2 2v5m-4 0h8M8 10h.01M12 8h.01M16 10h.01M5 7h.01M9 4h.01M15 4h.01M19 7h.01");
}

.w9ewxlbfh {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M12 15a2 2 0 1 1-.001-3.999A2 2 0 0 1 12 15");
}

</style>
