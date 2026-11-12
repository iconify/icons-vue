<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="z_nay2cuc"/><path class="op9ragiay"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:subnet-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.op9ragiay {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 13a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2v6a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2Zm7-8a2 2 0 1 0 4 0a2 2 0 0 0-4 0M7 16h.01M12 16h.01M17 16h.01M12 7v4");
}

.z_nay2cuc {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M9.236 3.832a3 3 0 1 1 5.527 2.338a3 3 0 0 1-5.527-2.338M5 10h14a3 3 0 0 1 3 3v6a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3v-6a3 3 0 0 1 3-3");
}

</style>
