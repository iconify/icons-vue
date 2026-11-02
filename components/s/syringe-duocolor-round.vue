<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qbbfq9kyc"/><path class="bfdr36f3u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:syringe-duocolor-round" /></template>
<style>
.bfdr36f3u {
  d: path("m13 7l-5 5a2.828 2.828 0 1 0 4 4l5-5m-5-5l6 6M8 16l-4 4m5-9l4 4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qbbfq9kyc {
  stroke-opacity: 0.4;
  d: path("m15 9l3-3m-2-2l4 4");
}

</style>
