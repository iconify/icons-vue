<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="gts3bwjeq"/><path class="nkpahgx6q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:phone-desk-duocolor" /></template>
<style>
.gts3bwjeq {
  stroke-opacity: 0.4;
  d: path("M15 5a2 2 0 0 1 2-2h2a2 2 0 0 1 2 2v14a2 2 0 0 1-2 2h-2a2 2 0 0 1-2-2Z");
}

.nkpahgx6q {
  d: path("M15 5H5a2 2 0 0 0-2 2v10a2 2 0 0 0 2 2h10M6 9h6m-6 4h.01M9 13h.01M12 13h.01M6 16h.01M9 16h.01M12 16h.01");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
