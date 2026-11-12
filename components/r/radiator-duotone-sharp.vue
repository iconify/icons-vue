<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="hzghdtbat"/><path class="q07rtpbqn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:radiator-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.hzghdtbat {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M6 3v18H4V3Zm7 0v18h-2V3Zm7 0v18h-2V3Z");
}

.q07rtpbqn {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 3h2v18H4Zm7 0h2v18h-2Zm7 0h2v18h-2ZM3 8h16M5 16h16");
}

</style>
