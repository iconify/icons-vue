<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="qsa49p7wx"/><path class="qon-qwb5l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:skyscraper-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.qon-qwb5l {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 21h18M8 21V5h2V3h4v2h2v16M12 8h.01M12 12h.01M12 16h.01");
}

.qsa49p7wx {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M8 5h2V3h4v2h2v16H8Z");
}

</style>
