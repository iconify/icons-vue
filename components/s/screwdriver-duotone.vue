<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ofa4fabxz"/><path class="rhhm9vz3o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:screwdriver-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ofa4fabxz {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m4 16l6-6a1.415 1.415 0 0 1 2 0l2 2a1.415 1.415 0 0 1 0 2l-6 6a2.828 2.828 0 1 1-4-4");
}

.rhhm9vz3o {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m4 16l6-6a1.414 1.414 0 0 1 2 0l2 2a1.414 1.414 0 0 1 0 2l-6 6a2.828 2.828 0 1 1-4-4m9-5l7-7");
}

</style>
