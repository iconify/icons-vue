<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="gl16ndboh"/><path class="iiel43b5s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:path-duocolor-round" /></template>
<style>
.gl16ndboh {
  stroke-opacity: 0.4;
  d: path("M3 18a3 3 0 1 0 6 0a3 3 0 0 0-6 0M15 6a3 3 0 1 0 6 0a3 3 0 0 0-6 0");
}

.iiel43b5s {
  d: path("M8.121 15.879L15.88 8.12");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
