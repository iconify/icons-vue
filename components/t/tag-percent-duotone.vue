<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="er7nthi_k"/><path class="rdm0h4bjd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tag-percent-duotone" /></template>
<style>
.er7nthi_k {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M18 21H6a1 1 0 0 1-1-1V7l4-4h6l4 4v13a1 1 0 0 1-1 1m-9-9a1 1 0 1 0 0-2a1 1 0 0 0 0 2m6 6a1 1 0 1 0 0-2a1 1 0 0 0 0 2");
}

.ft5dv1b6b {
  fill: none;
}

.rdm0h4bjd {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M19 14v6a1 1 0 0 1-1 1H6a1 1 0 0 1-1-1V7l4-4h6l4 4zm-8-8h2m2 5l-6 6m-1-6a1 1 0 1 0 2 0a1 1 0 0 0-2 0m6 6a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

</style>
