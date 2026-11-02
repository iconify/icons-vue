<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ks93_wbzu"/><path class="wlym12bam"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:taxi-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ks93_wbzu {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M9 19v1a1 1 0 0 1-1 1H6a1 1 0 0 1-1-1v-1.171A3 3 0 0 1 3 16v-4c0-.155.036-.308.106-.447l1-2C4.643 8.478 5.652 7.001 7 7h10c1.348.001 2.357 1.478 2.894 2.553l1 2c.07.139.106.292.106.447v4c0 1.27-.803 2.405-2 2.829V20a1 1 0 0 1-1 1h-2a1 1 0 0 1-1-1v-1Z");
}

.wlym12bam {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 5h4M8 15h.01M16 15h.01M12 18H6a2 2 0 0 1-2-2v-4l1-2c.613-1.226 1.387-2 2-2h10c.613 0 1.387.774 2 2l1 2v4a2 2 0 0 1-2 2zm-6 0h2v2H6Zm10 0h2v2h-2ZM3 12h18");
}

</style>
