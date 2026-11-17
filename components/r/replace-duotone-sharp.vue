<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="kp578ccuu"/><path class="f-ts_ybys"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:replace-duotone-sharp" /></template>
<style>
.f-ts_ybys {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 15h6v6H3ZM15 3h6v6h-6Zm-4 0H6v7M3 7l3 3l3-3");
}

.ft5dv1b6b {
  fill: none;
}

.kp578ccuu {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M3 15h6v6H3Z");
}

</style>
