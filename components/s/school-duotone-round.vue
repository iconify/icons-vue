<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="gh41apxjb"/><path class="aeb857bpq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:school-duotone-round" /></template>
<style>
.aeb857bpq {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m4 7l6-3a4.47 4.47 0 0 1 4 0l6 3M6 6v5l-3 2v4a4 4 0 0 0 4 4h10a4 4 0 0 0 4-4v-4l-3-2V6m-8 4a2 2 0 1 0 4 0a2 2 0 0 0-4 0m0 11v-3a2 2 0 1 1 4 0v3");
}

.ft5dv1b6b {
  fill: none;
}

.gh41apxjb {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M9.553 3.106a5.47 5.47 0 0 1 4.894 0l4 2A1 1 0 0 1 19 6v4.465l2.555 1.703A1 1 0 0 1 22 13v4a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 22H7a5 5 0 0 1-5-5v-4a1 1 0 0 1 .445-.832L5 10.465V6c0-.379.214-.725.553-.894Z");
}

</style>
