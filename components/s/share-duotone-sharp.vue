<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="deo_w_prh"/><path class="k8jv3ybuq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:share-duotone-sharp" /></template>
<style>
.deo_w_prh {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M4 10h16v11H4Z");
}

.ft5dv1b6b {
  fill: none;
}

.k8jv3ybuq {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 10H4v11h16V10h-3m-2-4l-3-3l-3 3m3-3v10");
}

</style>
