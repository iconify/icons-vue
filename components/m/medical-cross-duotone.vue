<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="u3ou2gbot"/><path class="oqbs3c23v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:medical-cross-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.oqbs3c23v {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m14 8.536l3.928-2.268a1 1 0 0 1 1.366.366l1 1.732a1 1 0 0 1-.366 1.366L16 12l3.928 2.268a1 1 0 0 1 .366 1.366l-1 1.732a1 1 0 0 1-1.366.366L14 15.464V20a1 1 0 0 1-1 1h-2a1 1 0 0 1-1-1v-4.536l-3.928 2.268a1 1 0 0 1-1.366-.366l-1-1.732a1 1 0 0 1 .366-1.366L8 12L4.072 9.732a1 1 0 0 1-.366-1.366l1-1.732a1 1 0 0 1 1.366-.366L10 8.536V4a1 1 0 0 1 1-1h2a1 1 0 0 1 1 1z");
}

.u3ou2gbot {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m15 6.804l2.428-1.402a2 2 0 0 1 2.732.732l1 1.732a2.003 2.003 0 0 1-.732 2.732L18 12l2.428 1.402a1.996 1.996 0 0 1 .732 2.732l-1 1.732a2 2 0 0 1-2.732.732L15 17.196V20a2 2 0 0 1-2 2h-2a2 2 0 0 1-2-2v-2.804l-2.428 1.402a2 2 0 0 1-2.732-.732l-1-1.732a2.003 2.003 0 0 1 .732-2.732L6 12l-2.428-1.402a1.996 1.996 0 0 1-.732-2.732l1-1.732a2 2 0 0 1 2.732-.732L9 6.804V4a2 2 0 0 1 2-2h2a2 2 0 0 1 2 2Z");
}

</style>
