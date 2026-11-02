<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="yp8_fcbqp"/><path class="uixisib2k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shift-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.uixisib2k {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 19h-2a1 1 0 0 1-1-1v-4a1 1 0 0 0-1-1H5c-.369 0-.369-.631 0-1l6-6a1.414 1.414 0 0 1 2 0l6 6c.369.369.369 1 0 1h-3a1 1 0 0 0-1 1v4a1 1 0 0 1-1 1z");
}

.yp8_fcbqp {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M9 18v-4a1 1 0 0 0-1-1H5c-.369 0-.369-.631 0-1l6-6a1.415 1.415 0 0 1 2 0l6 6c.369.369.369 1 0 1h-3a1 1 0 0 0-1 1v4a1 1 0 0 1-1 1h-4a1 1 0 0 1-1-1");
}

</style>
