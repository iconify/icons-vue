<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="d1ych6yli"/><path class="l0srflbyw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:scan-barcode-duocolor-sharp" /></template>
<style>
.d1ych6yli {
  stroke-opacity: 0.4;
  d: path("M7 8v8m5-8v8m5-8v8");
}

.l0srflbyw {
  d: path("M3 7V3h4m10 0h4v4m0 10v4h-4M7 21H3v-4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
