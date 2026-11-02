<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="jo-hlhtdr"/><path class="sig349bpy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:siren-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.jo-hlhtdr {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M17 16h2a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1v-4a1 1 0 0 1 1-1h2v-3a5 5 0 0 1 10 0Z");
}

.sig349bpy {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 17v-4a4 4 0 1 1 8 0v4M5 17h14v4H5Zm7-4v4m0-14v2M4 5l2 2m14-2l-2 2");
}

</style>
