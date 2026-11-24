<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ckjqj_b3x"/><path class="aeolmq3si"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:police-station-alt-duotone-sharp" /></template>
<style>
.aeolmq3si {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 21h18M5 21V3h14v18m-9 0v-4h4v4M12 6h3v2.625c0 2.063-1.312 3.375-3 4.125c-1.687-.75-3-2.062-3-4.125V6z");
}

.ckjqj_b3x {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M5 3h14v18H5Z");
}

.ft5dv1b6b {
  fill: none;
}

</style>
