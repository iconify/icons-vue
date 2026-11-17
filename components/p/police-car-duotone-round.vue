<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="jpabceb3d"/><path class="m0-qb8boy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:police-car-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.jpabceb3d {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M16 18H8v2H6v-2a2 2 0 0 1-2-2v-4l1-2c.569-1.137 1.695-1.999 3-2h8c1.305.001 2.431.863 3 2l1 2v4a2 2 0 0 1-2 2v2h-2Z");
}

.m0-qb8boy {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M11 8V6h2v2m-2 0h2M7 5h1m8 0h1M8 15h.01M16 15h.01M12 18H6a2 2 0 0 1-2-2v-4l1-2c.613-1.226 1.774-2 3-2h8c1.226 0 2.387.774 3 2l1 2v4a2 2 0 0 1-2 2zm-6 0h2v2H6Zm10 0h2v2h-2ZM3 12h18");
}

</style>
