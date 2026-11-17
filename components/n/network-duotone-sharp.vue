<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="rm372sb8s"/><path class="kqqk9gbuz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:network-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.kqqk9gbuz {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 3h6v5H9ZM3 16h6v5H3Zm12 0h6v5h-6Zm-3-8v4m-6 4v-4h12v4");
}

.rm372sb8s {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M9 3h6v5H9ZM3 16h6v5H3Zm12 0h6v5h-6Z");
}

</style>
