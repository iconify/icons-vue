<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="blpcn8bvp"/><path class="z-vehrbgo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:paint-bucket-duotone-sharp" /></template>
<style>
.blpcn8bvp {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m17 12l-8 8l-6-6l2-2Zm2 4c1 1 2 2 2 3a2 2 0 1 1-4 0c0-1 1-2 2-3");
}

.ft5dv1b6b {
  fill: none;
}

.z-vehrbgo {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m11 6l6 6l-8 8l-6-6zM8 3l3 3m-6 6h12m4 7a2 2 0 1 1-4 0c0-1 1-2 2-3c1 1 2 2 2 3");
}

</style>
