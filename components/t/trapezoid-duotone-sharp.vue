<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="knus06b_g"/><path class="o0n0yhb9c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:trapezoid-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.knus06b_g {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m3 3l18 4v10L3 21Z");
}

.o0n0yhb9c {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m3 3l18 4v10L3 21z");
}

</style>
