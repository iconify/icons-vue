<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="now253bdc"/><path class="qp-7rtbwd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mobile-foldable-duocolor-round" /></template>
<style>
.now253bdc {
  stroke-opacity: 0.4;
  d: path("M12 3v18");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qp-7rtbwd {
  d: path("M21 12v7l-7 2h-4l-7-2V5l7-2h4l7 2zM6 7h.01");
}

</style>
