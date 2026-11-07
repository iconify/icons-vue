<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="bvjdiob1q"/><path class="wmf5olupz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:pin-off-duotone-round" /></template>
<style>
.bvjdiob1q {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M11 3h5a2 2 0 1 1 0 4a1 1 0 0 0-.707.293Zm7 14H6a1 1 0 0 1-1-1v-1c.008-2.035 3.992-1.965 4-4V8a1 1 0 0 0-1-1a2.002 2.002 0 0 1-1.823-2.823l12.53 12.53A1 1 0 0 1 18 17");
}

.ft5dv1b6b {
  fill: none;
}

.wmf5olupz {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M11 3h5a2 2 0 1 1 0 4a1 1 0 0 0-.707.293m3.414 9.414A1 1 0 0 1 18 17H6a1 1 0 0 1-1-1v-1c0-2 4-2 4-4V8a1 1 0 0 0-1-1a2 2 0 0 1-1.823-2.823M12 17v4M4 2l18 18");
}

</style>
