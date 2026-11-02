<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pv-hghb8k"/><path class="u9ppe9baq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:receipt-duocolor-sharp" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pv-hghb8k {
  stroke-opacity: 0.4;
  d: path("M8 7h8m-8 4h8m-8 4h4");
}

.u9ppe9baq {
  d: path("M12 3h8v18l-2-2l-2 2l-2-2l-2 2l-2-2l-2 2l-2-2l-2 2V3z");
}

</style>
