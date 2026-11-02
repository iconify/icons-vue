<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="o5pw4w6ef"/><path class="vcn0ywbrs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:star-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.o5pw4w6ef {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m15 9l7 1l-5 5l1 6l-6-3l-6 3l1-6l-5-5l7-1l3-6Z");
}

.vcn0ywbrs {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m12 3l3 6l7 1l-5 5l1 6l-6-3l-6 3l1-6l-5-5l7-1Z");
}

</style>
