<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="d1jwc2b7m"/><path class="hsw_-dbyo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:suspension-railway-front-duotone-round" /></template>
<style>
.d1jwc2b7m {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M15 8a5 5 0 0 1 5 5v5a3 3 0 0 1-3 3H7a3 3 0 0 1-3-3v-5a5 5 0 0 1 5-5Z");
}

.ft5dv1b6b {
  fill: none;
}

.hsw_-dbyo {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 9h3a4 4 0 0 1 4 4v5a2 2 0 0 1-2 2H7a2 2 0 0 1-2-2v-5a4 4 0 0 1 4-4zm-7 5h14M3 4h18M9 4v5m6-5v5m-6 8h.01M15 17h.01");
}

</style>
