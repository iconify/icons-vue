<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="p89h92owj"/><path class="i-7ssyblh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:reddit-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.i-7ssyblh {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m12 10l1-6h4m0 0a1 1 0 1 0 2 0a1 1 0 0 0-2 0M9 14h.01M15 14h.01M9 17a5 5 0 0 0 6 0m-8.457-5.273C7.96 10.625 9.934 10 12 10s4.04.625 5.457 1.727a2 2 0 1 1 2.005 3.219c.288 2.087-1.068 4.113-3.496 5.222s-5.504 1.109-7.932 0s-3.784-3.135-3.496-5.222a2 2 0 1 1 2.005-3.219");
}

.p89h92owj {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M6.543 11.727c2.964-2.303 7.95-2.303 10.914 0a2 2 0 1 1 2.005 3.219c.288 2.087-1.068 4.113-3.496 5.222c-2.439 1.113-5.493 1.113-7.932 0c-2.428-1.109-3.784-3.135-3.496-5.222a2 2 0 1 1 2.005-3.219");
}

</style>
