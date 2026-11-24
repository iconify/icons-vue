<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="p06ikfbzw"/><path class="jehbp-bqn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:university-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.jehbp-bqn {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m20 6l-8 3l-8-3l8-3zM3 21h18M20 6v3M6 12v5m4-5v5m4-5v5m4-5v5");
}

.p06ikfbzw {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M12 9L4 6l8-3l8 3Z");
}

</style>
