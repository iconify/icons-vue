<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ypziembin"/><path class="iei9fyz5m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:package-warning-corner-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.iei9fyz5m {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 8v12h4M4 8l2-4h12l2 4M4 8h16m-3 6v4m0 3h.01");
}

.ypziembin {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M6 4h12l2 4H4Z");
}

</style>
