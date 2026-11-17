<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="e8yjl_t7g"/><path class="sfj3jr60e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:thumbs-down-duotone-round" /></template>
<style>
.e8yjl_t7g {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M7 14H5a2 2 0 0 1-2-2V5a2 2 0 1 1 4 0a2 2 0 0 1 2-2h8c1.512 0 2.767.837 3 2l1 5v1a3 3 0 0 1-3 3h-1a2 2 0 0 0-2 2v3a2 2 0 1 1-4 0v-1a4 4 0 0 0-4-4");
}

.ft5dv1b6b {
  fill: none;
}

.sfj3jr60e {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 14a4 4 0 0 1 4 4v1a2 2 0 1 0 4 0v-3a2 2 0 0 1 2-2h1a3 3 0 0 0 3-3v-1l-1-5c-.233-1.163-1.488-2-3-2H9a2 2 0 0 0-2 2m0 9H5a2 2 0 0 1-2-2V5a2 2 0 1 1 4 0z");
}

</style>
