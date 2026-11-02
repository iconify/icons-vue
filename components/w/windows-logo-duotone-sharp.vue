<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="avu59xt4u"/><path class="kb2fxybse"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:windows-logo-duotone-sharp" /></template>
<style>
.avu59xt4u {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M20.89 4.006A1 1 0 0 1 22 5v14a1 1 0 0 1-1.11.994l-18-2A1 1 0 0 1 2 17V7a1 1 0 0 1 .89-.994Z");
}

.ft5dv1b6b {
  fill: none;
}

.kb2fxybse {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 6v12m-9-6h18M3 7l18-2v14L3 17Z");
}

</style>
