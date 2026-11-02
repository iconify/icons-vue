<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="mi5da4b0e"/><path class="qv67hybap"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:zap-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.mi5da4b0e {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M15 3v7h5a1.002 1.002 0 0 1 .707 1.707l-10 10A1 1 0 0 1 9 21v-7H4a1.002 1.002 0 0 1-.707-1.707l10-10A1 1 0 0 1 15 3");
}

.qv67hybap {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14 3L4 13h6v8l10-10h-6z");
}

</style>
