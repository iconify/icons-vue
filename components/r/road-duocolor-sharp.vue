<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lo0jysz2y"/><path class="bz7kdbcmf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:road-duocolor-sharp" /></template>
<style>
.bz7kdbcmf {
  d: path("M3 21L9 3m12 18L15 3");
}

.lo0jysz2y {
  stroke-opacity: 0.4;
  d: path("M12 7v2m0 4v2m0 4v2");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
