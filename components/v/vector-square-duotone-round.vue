<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="xmmcdfmqh"/><path class="zecyhmblu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:vector-square-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.xmmcdfmqh {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M17 5v2h2v10h-2v2H7v-2H5V7h2V5Z");
}

.zecyhmblu {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 5h10m2 2v10m-2 2H7m-2-2V7M3 5a2 2 0 1 1 4 0a2 2 0 0 1-4 0m14 0a2 2 0 1 1 4 0a2 2 0 0 1-4 0m0 14a2 2 0 1 1 4 0a2 2 0 0 1-4 0M3 19a2 2 0 1 1 4 0a2 2 0 0 1-4 0");
}

</style>
