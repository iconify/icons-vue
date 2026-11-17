<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="chfyw2b4v"/><path class="mxw94vbvu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:note-clock-corner-duotone-sharp" /></template>
<style>
.chfyw2b4v {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M4 4h16v4H8v12H4Z");
}

.ft5dv1b6b {
  fill: none;
}

.mxw94vbvu {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 20H4V4h16v4m-8 9a5 5 0 1 0 10 0a5 5 0 0 0-10 0m5-2v2h2");
}

</style>
