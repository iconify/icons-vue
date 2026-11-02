<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="t509wxcjg"/><path class="mf0i_gb5l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:star-half-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.mf0i_gb5l {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m12 3l3 6l7 1l-5 5l1 6l-6-3l-6 3l1-6l-5-5l7-1Zm0 0v15");
}

.t509wxcjg {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M13 18a1 1 0 0 1-.553.894l-6 3a1 1 0 0 1-1.041-.09a1 1 0 0 1-.392-.968l.915-5.493l-4.636-4.636a1.001 1.001 0 0 1 .566-1.697l6.481-.926l2.766-5.531A.998.998 0 0 1 13 3Z");
}

</style>
