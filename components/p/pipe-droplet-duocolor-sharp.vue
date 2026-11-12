<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vzgwh6bxm"/><path class="v6eiu0bth"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:pipe-droplet-duocolor-sharp" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.v6eiu0bth {
  d: path("M3 3h5l2 3l-2 3H3m18-6h-5l-2 3l2 3h5");
}

.vzgwh6bxm {
  stroke-opacity: 0.4;
  d: path("m12 13l-3 4c0 4 6 4 6 0Z");
}

</style>
