<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ru787lbrb"/><path class="vmuvplbiq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:puzzle-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ru787lbrb {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M21 7v5a2.235 2.235 0 1 0 0 4v5H7v-5a2.235 2.235 0 1 1 0-4V7h5a2.235 2.235 0 1 1 4 0Z");
}

.vmuvplbiq {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16 7h5v5a2.236 2.236 0 1 0 0 4v5H7v-5a2.236 2.236 0 1 1 0-4V7h5a2.236 2.236 0 1 1 4 0");
}

</style>
