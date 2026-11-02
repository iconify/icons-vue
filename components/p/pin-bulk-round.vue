<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="pojhp1bzu"/><path class="l_k3x8bzp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:pin-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.l_k3x8bzp {
  d: path("M13 17v4a1 1 0 0 1-2 0v-4a1 1 0 0 1 2 0");
}

.pojhp1bzu {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8 2h8a3 3 0 1 1 0 6v3c0 .179.137.312.265.419c.339.282.79.49 1.182.687c.544.272 1.098.547 1.568.938c.606.505.985 1.154.985 1.956v1a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2v-1c0-.802.379-1.451.985-1.956c.47-.391 1.024-.666 1.568-.938c.392-.197.843-.405 1.182-.687c.128-.107.265-.24.265-.419V8a3 3 0 1 1 0-6");
}

</style>
