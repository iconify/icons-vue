<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="kdg-rhzef"/><path class="j_mgj6g9r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:skip-back-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.j_mgj6g9r {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m16.94 5.304l-8 5a2 2 0 0 0 0 3.392l8 5C18.272 19.529 20 18.571 20 17V7c0-1.57-1.728-2.529-3.06-1.696M4 5v14");
}

.kdg-rhzef {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M16.94 5.304A2 2 0 0 1 20 7v10a2 2 0 0 1-3.06 1.696l-8-5a1.998 1.998 0 0 1 0-3.392Z");
}

</style>
