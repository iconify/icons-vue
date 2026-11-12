<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ls_43mben"/><path class="f3zr3mbrg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:window-sync-corner-duotone-round" /></template>
<style>
.f3zr3mbrg {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 8a4 4 0 0 1 4-4h10a4 4 0 0 1 4 4M8 20H7a4 4 0 0 1-4-4V8m0 0h18m0 11a4.472 4.472 0 0 1-8 0m3 0h-3v3m0-7a4.472 4.472 0 0 1 8 0m-3 0h3v-3");
}

.ft5dv1b6b {
  fill: none;
}

.ls_43mben {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M3 9a1 1 0 0 1-1-1a5 5 0 0 1 1.464-3.536A4.98 4.98 0 0 1 7 3h10c1.33 0 2.597.522 3.536 1.464A5 5 0 0 1 22 8a1 1 0 0 1-1 1Z");
}

</style>
