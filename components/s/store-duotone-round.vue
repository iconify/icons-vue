<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="qqc7wbbuf"/><path class="oj66n_imi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:store-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.oj66n_imi {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 6a3 3 0 0 1 3-3h12a3 3 0 0 1 0 6H6a3 3 0 0 1-3-3m2 3v8a4 4 0 0 0 4 4h6a4 4 0 0 0 4-4V9m-9 12v-4a2 2 0 1 1 4 0v4M9 3v6m6-6v6");
}

.qqc7wbbuf {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M6 3h12a3 3 0 1 1 0 6H6a3 3 0 1 1 0-6");
}

</style>
