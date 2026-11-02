<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="pi6e2tbte"/><path class="a5vhhab8y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:more-horizontal-duotone" /></template>
<style>
.a5vhhab8y {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 12a1 1 0 1 0 2 0a1 1 0 0 0-2 0m6 0a1 1 0 1 0 2 0a1 1 0 0 0-2 0m6 0a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

.ft5dv1b6b {
  fill: none;
}

.pi6e2tbte {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M6 13a1 1 0 1 1 0-2a1 1 0 0 1 0 2m6 0a1 1 0 1 1 0-2a1 1 0 0 1 0 2m6 0a1 1 0 1 1 0-2a1 1 0 0 1 0 2");
}

</style>
