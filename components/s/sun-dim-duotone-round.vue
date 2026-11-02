<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="wql_3nbpq"/><path class="mxgfszb4w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:sun-dim-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.mxgfszb4w {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 12a3 3 0 1 0 6 0a3 3 0 0 0-6 0m10 0h.01m-2.06 4.95h.01M12 19h.01m-4.96-2.05h.01M5 12h.01m2.04-4.95h.01M12 5h.01m4.94 2.05h.01");
}

.wql_3nbpq {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M9 12a3 3 0 1 1 6 0a3 3 0 0 1-6 0");
}

</style>
