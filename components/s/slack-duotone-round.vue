<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="cbcrotb3z"/><path class="kthkii72m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:slack-duotone-round" /></template>
<style>
.cbcrotb3z {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M12 6a2 2 0 1 1 4 0v4a2 2 0 1 1 2 2a2 2 0 1 1 0 4h-4a2 2 0 1 1-2 2a2 2 0 1 1-4 0v-4a2 2 0 1 1-2-2a2 2 0 1 1 0-4h4a2 2 0 1 1 2-2");
}

.ft5dv1b6b {
  fill: none;
}

.kthkii72m {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 8h-2a2 2 0 1 1 2-2Zm4 4v-2a2 2 0 1 1 2 2Zm-4 4h2a2 2 0 1 1-2 2Zm-4-4v2a2 2 0 1 1-2-2Zm8-2V6a2 2 0 1 0-4 0m0 2v8m0 2a2 2 0 1 1-4 0v-4m2-6H6a2 2 0 1 0 0 4m2 0h8m2 0a2 2 0 1 1 0 4h-4");
}

</style>
