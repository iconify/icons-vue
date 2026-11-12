<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="qnv6xeydd"/><path class="cghazsbjc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tag-plus-duotone-round" /></template>
<style>
.cghazsbjc {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M19 14v5a2 2 0 0 1-2 2H7a2 2 0 0 1-2-2V8c0-.64.36-1.36 1-2l2-2c.64-.64 1.36-1 2-1h4c.64 0 1.36.36 2 1l2 2c.64.64 1 1.36 1 2zm-8-8h2m-4 8h6m-3-3v6");
}

.ft5dv1b6b {
  fill: none;
}

.qnv6xeydd {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M19 14v5a2 2 0 0 1-2 2H7a2 2 0 0 1-2-2V8c0-.763.48-1.479 1-2l2-2c.521-.52 1.237-1 2-1h4c.763 0 1.479.48 2 1l2 2c.52.521 1 1.237 1 2Z");
}

</style>
