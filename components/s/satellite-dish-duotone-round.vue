<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="u-6vr7q-z"/><path class="udjp6gmkm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:satellite-dish-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.u-6vr7q-z {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m5.707 10.293l8 8a1 1 0 0 1 0 1.414a6.6 6.6 0 0 1-2.203 1.462A6.6 6.6 0 0 1 9 21.657a6.64 6.64 0 0 1-4.707-1.95A6.64 6.64 0 0 1 2.343 15a6.6 6.6 0 0 1 .488-2.504a6.6 6.6 0 0 1 1.462-2.203a.997.997 0 0 1 1.414 0");
}

.udjp6gmkm {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13 19a5.657 5.657 0 1 1-8-8Zm-4-4l4-4m0-4a4 4 0 0 1 4 4m-4-8a8 8 0 0 1 8 8");
}

</style>
