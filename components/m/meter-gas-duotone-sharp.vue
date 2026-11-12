<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="oj70tvpuz"/><path class="e38sj9bvt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:meter-gas-duotone-sharp" /></template>
<style>
.e38sj9bvt {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 3h14v18H5Zm-2 9h2m14 0h2m-9-5.4c.3 1.5 1.2 2.7 2.4 3.6c.9.9 1.2 2.1 1.2 3.6a3.6 3.6 0 1 1-7.2 0c0-.9.3-1.5.6-1.8a1.2 1.2 0 0 0 2.4 0c0-.9-.3-1.2-.6-1.8c-.6-1.2-.3-2.4 1.2-3.6");
}

.ft5dv1b6b {
  fill: none;
}

.oj70tvpuz {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M4 21V3a1 1 0 0 1 1-1h14a1 1 0 0 1 1 1v18a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1");
}

</style>
