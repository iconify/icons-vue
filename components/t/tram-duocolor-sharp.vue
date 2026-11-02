<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rp_vibb3t"/><path class="hpiexqxwl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tram-duocolor-sharp" /></template>
<style>
.hpiexqxwl {
  d: path("M5 7h14v12H5zm3 12l-1 2m9-2l1 2M5 13h14");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rp_vibb3t {
  stroke-opacity: 0.4;
  d: path("M9 3h6m-3 0v4m-3 9h.01M15 16h.01");
}

</style>
