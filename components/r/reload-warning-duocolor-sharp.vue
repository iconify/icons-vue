<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="furh41jlz"/><path class="axh2ttbuy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:reload-warning-duocolor-sharp" /></template>
<style>
.axh2ttbuy {
  d: path("M20 8A8.944 8.944 0 0 0 4 8m4 0H4V4m0 12a8.944 8.944 0 0 0 16 0m-4 0h4v4");
}

.furh41jlz {
  stroke-opacity: 0.4;
  d: path("M12 8v5m0 3h.01");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
