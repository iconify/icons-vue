<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="u1-9ero-a"/><path class="vbqjzrblc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:subnet-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.u1-9ero-a {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M9.236 3.832a3 3 0 1 1 5.527 2.338a3 3 0 0 1-5.527-2.338M7 10h10a5 5 0 0 1 5 5v2a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 22H7a5 5 0 0 1-5-5v-2a5 5 0 0 1 5-5");
}

.vbqjzrblc {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 15a4 4 0 0 1 4-4h10a4 4 0 0 1 4 4v2a4 4 0 0 1-4 4H7a4 4 0 0 1-4-4Zm7-10a2 2 0 1 0 4 0a2 2 0 0 0-4 0M7 16h.01M12 16h.01M17 16h.01M12 7v4");
}

</style>
