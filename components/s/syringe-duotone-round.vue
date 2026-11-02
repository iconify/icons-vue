<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="q51yqcd8a"/><path class="st-jtccqc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:syringe-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.q51yqcd8a {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M13.707 14.293a1 1 0 0 1 0 1.414l-1 1a3.828 3.828 0 0 1-5.414-5.414l1-1a1 1 0 0 1 1.414 0Z");
}

.st-jtccqc {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m13 7l-5 5a2.828 2.828 0 1 0 4 4l5-5m-5-5l6 6M8 16l-4 4m5-9l4 4m2-6l3-3m-2-2l4 4");
}

</style>
