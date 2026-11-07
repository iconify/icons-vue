<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="goqqv5b7k"/><path class="q7bsalbeg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:phone-off-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.goqqv5b7k {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m10.5 13.5l-2.814 2.814A15.95 15.95 0 0 1 3 5a2.003 2.003 0 0 1 2-2h1c1.837.002 3.342 1.36 4 3c.693 1.733.693 3.307 0 4a2.12 2.12 0 0 0 0 3Zm7.5.5h1c1.105 0 2 1.791 2 4v1a2.003 2.003 0 0 1-2 2a15.94 15.94 0 0 1-7.911-2.089L15 15c.77-.768 1.95-1 3-1");
}

.q7bsalbeg {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.686 16.314A15.95 15.95 0 0 1 3 5a2 2 0 0 1 2-2h1c1.691 0 3.275 1.188 4 3c.693 1.733.693 3.307 0 4a2.12 2.12 0 0 0 0 3l.5.5M15 15c.64-.64 1.72-1 3-1h1c1.105 0 2 1.79 2 4v1a2 2 0 0 1-2 2c-2.878 0-5.578-.76-7.91-2.09M2 22L22 2");
}

</style>
