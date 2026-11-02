<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vorzg9apl"/><path class="yyki1gvbo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:presentation-duocolor-sharp" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vorzg9apl {
  stroke-opacity: 0.4;
  d: path("m12 16l-5 5m5-5l5 5");
}

.yyki1gvbo {
  d: path("M5 3v13h14V3M3 3h18");
}

</style>
