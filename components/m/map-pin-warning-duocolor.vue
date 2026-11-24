<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="kryytllqq"/><path class="pmsjm7ivf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:map-pin-warning-duocolor" /></template>
<style>
.kryytllqq {
  stroke-opacity: 0.4;
  d: path("M12 7v3m0 3h.01");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pmsjm7ivf {
  d: path("M12 21c-3-2-7-6-7-11a7 7 0 0 1 14 0c0 5-4 9-7 11");
}

</style>
