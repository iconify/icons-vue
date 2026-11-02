<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="pul5gegza"/><path class="rs0f_qurf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mouse-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.pul5gegza {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M6 9a6 6 0 1 1 12 0v6a6 6 0 1 1-12 0Z");
}

.rs0f_qurf {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 9a6 6 0 1 1 12 0v6a6 6 0 1 1-12 0Zm6-2v3");
}

</style>
