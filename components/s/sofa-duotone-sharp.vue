<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="d8v19ccab"/><path class="d42mhf9ye"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:sofa-duotone-sharp" /></template>
<style>
.d42mhf9ye {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 11v6h18v-6a2 2 0 1 0-4 0v2H7v-2a2 2 0 1 0-4 0m2 6v2m14-2v2M12 5v8M5 9V5h14v4");
}

.d8v19ccab {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M8 11v1h8v-1a3 3 0 1 1 6 0v6a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1v-6a3 3 0 1 1 6 0");
}

.ft5dv1b6b {
  fill: none;
}

</style>
