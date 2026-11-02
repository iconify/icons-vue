<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="bd8-9xbdm"/><path class="sjdtbpbtg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shower-duotone-round" /></template>
<style>
.bd8-9xbdm {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m13.707 7.707l-6 6a1 1 0 0 1-1.414 0a5.2 5.2 0 0 1-1.152-1.735A5.2 5.2 0 0 1 4.757 10a5.23 5.23 0 0 1 1.536-3.707A5.23 5.23 0 0 1 10 4.757a5.2 5.2 0 0 1 1.972.384c.65.263 1.241.655 1.735 1.152a1 1 0 0 1 0 1.414");
}

.ft5dv1b6b {
  fill: none;
}

.sjdtbpbtg {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13 7a4.243 4.243 0 0 0-6 6ZM4 4l3 3m3 9h.01M13 13h.01M16 10h.01M11 20h.01M14 17h.01M17 14h.01M20 11h.01");
}

</style>
