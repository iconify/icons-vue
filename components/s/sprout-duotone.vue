<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="nw41u3ufb"/><path class="b7us8fvra"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:sprout-duotone" /></template>
<style>
.b7us8fvra {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 10a6 6 0 0 0-6-6H3v2a6 6 0 0 0 6 6h3Zm0 4a6 6 0 0 1 6-6h3v1a6 6 0 0 1-6 6h-3Zm0 6V10");
}

.ft5dv1b6b {
  fill: none;
}

.nw41u3ufb {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M11.07 13H9a7 7 0 0 1-7-7V4a1 1 0 0 1 1-1h3a7.005 7.005 0 0 1 6.95 6.153A6.97 6.97 0 0 1 18 7h3a1 1 0 0 1 1 1v1a7 7 0 0 1-7 7h-3a1 1 0 0 1-1-1v-1q0-.503.07-1");
}

</style>
