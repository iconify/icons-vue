<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="bgluqxsnp"/><path class="ifj1jkb8e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:note-duotone-round" /></template>
<style>
.bgluqxsnp {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M13.707 20.707A1 1 0 0 1 13 21H8a5 5 0 0 1-5-5V8a5 5 0 0 1 5-5h8a5 5 0 0 1 5 5v5c0 .265-.105.52-.293.707ZM15 13a2 2 0 0 0-2 2v4l6-6Z");
}

.ft5dv1b6b {
  fill: none;
}

.ifj1jkb8e {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13 20H8a4 4 0 0 1-4-4V8a4 4 0 0 1 4-4h8a4 4 0 0 1 4 4v5m0 0l-7 7m0 0v-5a2 2 0 0 1 2-2h5");
}

</style>
