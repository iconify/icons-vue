<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="fry1f-b0f"/><path class="e3tw7yb0w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tag-percent-duotone-sharp" /></template>
<style>
.e3tw7yb0w {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 3h6l4 4v14H5V7zm2 3h2m2 5l-6 6m-1-6a1 1 0 1 0 2 0a1 1 0 0 0-2 0m6 6a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

.fry1f-b0f {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m15 3l4 4v14H5V7l4-4Zm-6 9a1 1 0 1 0 0-2a1 1 0 0 0 0 2m6 6a1 1 0 1 0 0-2a1 1 0 0 0 0 2");
}

.ft5dv1b6b {
  fill: none;
}

</style>
