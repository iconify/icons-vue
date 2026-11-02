<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="x0b38wjok"/><path class="jc3ecvb3z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:moon-star-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.jc3ecvb3z {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M21 12a9 9 0 1 1-9-9a6.403 6.403 0 0 0 9 9m-4-8c0 1 2 3 3 3c-1 0-3 2-3 3c0-1-2-3-3-3c1 0 3-2 3-3");
}

.x0b38wjok {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M22 12c0 5.523-4.477 10-10 10S2 17.523 2 12S6.477 2 12 2a1 1 0 0 1 .781 1.625a5.4 5.4 0 0 0 .844 7.594a5.4 5.4 0 0 0 6.75 0A1 1 0 0 1 22 12m-5-8c.002 1.005 1.995 2.998 3 3c-1.005.002-2.998 1.995-3 3c-.002-1.005-1.995-2.998-3-3c1.005-.002 2.998-1.995 3-3");
}

</style>
