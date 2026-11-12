<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jx-a7achz"/><path class="gyaiv24xg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:meter-gas-duocolor-sharp" /></template>
<style>
.gyaiv24xg {
  d: path("M5 3h14v18H5Zm-2 9h2m14 0h2");
}

.jx-a7achz {
  stroke-opacity: 0.4;
  d: path("M12 6.6c.3 1.5 1.2 2.7 2.4 3.6c.9.9 1.2 2.1 1.2 3.6a3.6 3.6 0 1 1-7.2 0c0-.9.3-1.5.6-1.8a1.2 1.2 0 0 0 2.4 0c0-.9-.3-1.2-.6-1.8c-.6-1.2-.3-2.4 1.2-3.6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
