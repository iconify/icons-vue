<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="qk1k811vr"/><path class="jxqnt6bqy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:whatsapp-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.jxqnt6bqy {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M11 9H9v1a5 5 0 0 0 5 5h1v-2M3 21l1-5a8.944 8.944 0 1 1 4 4Z");
}

.qk1k811vr {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M2.954 16.131a9.945 9.945 0 1 1 4.915 4.915l-4.673.935a1 1 0 0 1-1.177-1.177Z");
}

</style>
