<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="e73v7exke"/><path class="rgf-g2rup"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:thumbs-down-duotone" /></template>
<style>
.e73v7exke {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M2 12V5a3.001 3.001 0 0 1 5-2.236A3 3 0 0 1 9 2h8c.601 0 1.205.111 1.746.382c.543.271 1.007.716 1.203 1.302l2 6A1 1 0 0 1 22 10v2a3 3 0 0 1-3 3h-2a.997.997 0 0 0-1 1v3a3 3 0 1 1-6 0v-1a3 3 0 0 0-3-3H5a3 3 0 0 1-3-3");
}

.ft5dv1b6b {
  fill: none;
}

.rgf-g2rup {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 14a4 4 0 0 1 4 4v1a2 2 0 1 0 4 0v-3a2 2 0 0 1 2-2h2a2 2 0 0 0 2-2v-2l-2-6c-.2-.597-1.005-1-2-1H9a2 2 0 0 0-2 2m0 9H5a2 2 0 0 1-2-2V5a2 2 0 1 1 4 0z");
}

</style>
