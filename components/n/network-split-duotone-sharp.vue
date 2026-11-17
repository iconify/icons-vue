<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="uvgm_3bus"/><path class="f4mqir2bj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:network-split-duotone-sharp" /></template>
<style>
.f4mqir2bj {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 5a2 2 0 1 0 4 0a2 2 0 0 0-4 0m2 2v5m-6 8v-8h12v8M3 17l3 3l3-3m6 0l3 3l3-3");
}

.ft5dv1b6b {
  fill: none;
}

.uvgm_3bus {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M12 7a2 2 0 1 1-.001-3.999A2 2 0 0 1 12 7");
}

</style>
