<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ajdtnkbyp"/><path class="uust_ab9w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:wheelchair-duotone-sharp" /></template>
<style>
.ajdtnkbyp {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M8 4a1 1 0 1 1 2 0a1 1 0 0 1-2 0");
}

.ft5dv1b6b {
  fill: none;
}

.uust_ab9w {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 4a1 1 0 1 0 2 0a1 1 0 0 0-2 0m1 4v6h6l3 6h2M9 10h5m-5 1a5 5 0 1 0 4 8");
}

</style>
