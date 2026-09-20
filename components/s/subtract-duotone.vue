<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="qp6hzac1x"/><path class="a57d1w9hh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:subtract-duotone" /></template>
<style>
.a57d1w9hh {
  d: path("M174.63 81.35a80 80 0 1 0-93.28 93.28a80 80 0 1 0 93.28-93.28M32 96a64 64 0 1 1 64 64a64.07 64.07 0 0 1-64-64m128 128a63.81 63.81 0 0 1-62-48a80.07 80.07 0 0 0 78-78a64 64 0 0 1-16 126");
}

.cuyn6tgcc {
  fill: currentColor;
}

.qp6hzac1x {
  d: path("M232 160a72 72 0 0 1-143.6 7.6a73 73 0 0 0 7.6.4a72 72 0 0 0 72-72a73 73 0 0 0-.4-7.6A72 72 0 0 1 232 160");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
