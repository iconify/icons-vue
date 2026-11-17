<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="qnv6xeydd"/><path class="k9ny05utx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tag-star-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.k9ny05utx {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M19 14v5a2 2 0 0 1-2 2H7a2 2 0 0 1-2-2V8c0-.64.36-1.36 1-2l2-2c.64-.64 1.36-1 2-1h4c.64 0 1.36.36 2 1l2 2c.64.64 1 1.36 1 2zm-8-8h2m-1 3.9l1.2 2.4l2.8.4l-2 2l.4 2.4l-2.4-1.2l-2.4 1.2l.4-2.4l-2-2l2.8-.4Z");
}

.qnv6xeydd {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M19 14v5a2 2 0 0 1-2 2H7a2 2 0 0 1-2-2V8c0-.763.48-1.479 1-2l2-2c.521-.52 1.237-1 2-1h4c.763 0 1.479.48 2 1l2 2c.52.521 1 1.237 1 2Z");
}

</style>
