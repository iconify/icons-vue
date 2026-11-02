<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="sr6trvpei"/><path class="uw8epd3vo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:zap-off-duocolor" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.sr6trvpei {
  stroke-opacity: 0.4;
  d: path("m2 5l17 17");
}

.uw8epd3vo {
  d: path("m7 10l-2 2c-.369.369-.369 1 0 1h4a1 1 0 0 1 1 1v6c0 .369.631.369 1 0l3-3m3-3l2-2c.369-.369.369-1 0-1h-4a1 1 0 0 1-1-1V4c0-.369-.631-.369-1 0l-3 3");
}

</style>
