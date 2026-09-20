<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vywsisw8a"/><path class="p4j9py9tw"/><path class="d0l4pqiqc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:ocean-plastic-outline-regular" /></template>
<style>
.d0l4pqiqc {
  d: path("m3 18 3 -3 3 3 3 -3 3 3 3 -3 3 3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p4j9py9tw {
  d: path("M10.5 5V2h3v3");
}

.vywsisw8a {
  d: path("M9 5v9h6V5Z");
}

</style>
