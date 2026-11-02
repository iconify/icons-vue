<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="kct2wnb2f"/><path class="raj_h6ido"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:thermometer-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.kct2wnb2f {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M7 5a2 2 0 1 1 4 0v7a4.473 4.473 0 1 1-4 0Z");
}

.raj_h6ido {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 12V5a2 2 0 1 1 4 0v7a4.472 4.472 0 1 1-4 0m8-8h4m-4 3h2m-2 3h4");
}

</style>
