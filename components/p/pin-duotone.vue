<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="veolxhbmk"/><path class="xnjprmbiw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:pin-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.veolxhbmk {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M16 2a3 3 0 1 1 0 6v3c0 .179.137.312.265.419c.339.282.79.49 1.182.687c.544.272 1.098.547 1.568.938c.606.505.985 1.154.985 1.956v1a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2v-1c0-.802.379-1.451.985-1.956c.47-.391 1.024-.666 1.568-.938c.392-.197.843-.405 1.182-.687c.128-.107.265-.24.265-.419V8a3 3 0 1 1 0-6Z");
}

.xnjprmbiw {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 3h4a2 2 0 1 1 0 4a1 1 0 0 0-1 1v3c0 2 4 2 4 4v1a1 1 0 0 1-1 1H6a1 1 0 0 1-1-1v-1c0-2 4-2 4-4V8a1 1 0 0 0-1-1a2 2 0 1 1 0-4Zm0 14v4");
}

</style>
