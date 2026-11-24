<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="soagsix4r"/><path class="zlf8qhi9f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:police-station-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.soagsix4r {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M5 21V7a4 4 0 0 1 4-4h6a4 4 0 0 1 4 4v14Z");
}

.zlf8qhi9f {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 21h18M5 21V7a4 4 0 0 1 4-4h6a4 4 0 0 1 4 4v14m-9 0v-2a2 2 0 1 1 4 0v2M12 6.4l1.2 2.4l2.8.4l-2 2l.4 2.4l-2.4-1.2l-2.4 1.2l.4-2.4l-2-2l2.8-.4Z");
}

</style>
