<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qdy_ubbsn"/><path class="u5jhcyb0v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:weight-duocolor-sharp" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qdy_ubbsn {
  stroke-opacity: 0.4;
  d: path("M12 8a2 2 0 1 1 0-4m0 0a2 2 0 1 1 0 4");
}

.u5jhcyb0v {
  d: path("M7 8h10l3 12H4z");
}

</style>
