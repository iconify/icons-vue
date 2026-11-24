<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wp820wbfk"/><path class="dx06zimdd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:skyscraper-duocolor-sharp" /></template>
<style>
.dx06zimdd {
  d: path("M3 21h18M8 21V5h2V3h4v2h2v16");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.wp820wbfk {
  stroke-opacity: 0.4;
  d: path("M12 8h.01M12 12h.01M12 16h.01");
}

</style>
