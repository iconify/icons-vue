<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="tvv2qzbke"/><path class="kn9oo0b9m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tree-pine-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.kn9oo0b9m {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m14 7l4 4c.369.369.369 1 0 1h-3l5 5c.369.369.369 1 0 1H4c-.369 0-.369-.631 0-1l5-5H6c-.369 0-.369-.631 0-1l4-4H7l5-4l5 4zm-2 11v3");
}

.tvv2qzbke {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M18 11c.369.369.369 1 0 1h-3l5 5c.369.369.369 1 0 1H4c-.369 0-.369-.631 0-1l5-5H6c-.369 0-.369-.631 0-1l4-4H7l5-4l5 4h-3Z");
}

</style>
