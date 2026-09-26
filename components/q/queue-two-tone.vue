<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jsp63q5wp"/><path class="u8kg8-2of"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:queue-two-tone" /></template>
<style>
.jsp63q5wp {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 3L20 3C21.65685 3 23 4.34315 23 6L23 10C23 11.65685 21.65685 13 20 13L4 13C2.34315 13 1 11.65685 1 10L1 6C1 4.34315 2.34315 3 4 3Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.u8kg8-2of {
  d: path("M4 4L20 4C21.10457 4 22 4.89543 22 6L22 10C22 11.10457 21.10457 12 20 12L4 12C2.89543 12 2 11.10457 2 10L2 6C2 4.89543 2.89543 4 4 4ZM2 16H22M2 20H17");
}

</style>
