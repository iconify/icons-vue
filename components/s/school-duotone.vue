<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="fwzzsccxv"/><path class="xv_becbox"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:school-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.fwzzsccxv {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M11.553 2.106a1 1 0 0 1 .894 0l6 3A1 1 0 0 1 19 6v4.465l2.555 1.703A1 1 0 0 1 22 13v6a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3v-6a1 1 0 0 1 .445-.832L5 10.465V6c0-.379.214-.725.553-.894Z");
}

.xv_becbox {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m4 7l8-4l8 4M6 6v5l-3 2v6a2 2 0 0 0 2 2h14a2 2 0 0 0 2-2v-6l-3-2V6m-8 4a2 2 0 1 0 4 0a2 2 0 0 0-4 0m0 11v-3a2 2 0 1 1 4 0v3");
}

</style>
