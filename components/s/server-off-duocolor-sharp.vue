<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="e72o9db0j"/><path class="hqtu6d5sr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:server-off-duocolor-sharp" /></template>
<style>
.e72o9db0j {
  stroke-opacity: 0.4;
  d: path("M7 17h.01M2 2l20 20");
}

.hqtu6d5sr {
  d: path("M10 10H3V3m7 1h11v6h-5m4 10H3v-6h11");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
