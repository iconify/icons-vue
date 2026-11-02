<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="bnnbqxb0b"/><path class="k5023wk9m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tram-duotone-round" /></template>
<style>
.bnnbqxb0b {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M15 6a5 5 0 0 1 5 5v6a3 3 0 0 1-3 3H7a3 3 0 0 1-3-3v-6a5 5 0 0 1 5-5Z");
}

.ft5dv1b6b {
  fill: none;
}

.k5023wk9m {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 7h3a4 4 0 0 1 4 4v6a2 2 0 0 1-2 2H7a2 2 0 0 1-2-2v-6a4 4 0 0 1 4-4zM8 19l-1 2m9-2l1 2M5 13h14M9 3h6m-3 0v4m-3 9h.01M15 16h.01");
}

</style>
