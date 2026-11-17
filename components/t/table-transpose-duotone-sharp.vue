<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="n59kl09ow"/><path class="rz1w-eb1w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:table-transpose-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.n59kl09ow {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M11 3h10v4H11Zm-8 8h4v10H3Z");
}

.rz1w-eb1w {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M11 3h10v4H11Zm-8 8h4v10H3Zm15 8h-4v-4m0 4l6-6");
}

</style>
