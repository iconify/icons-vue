<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="qm04bxb0u"/><path class="vywsisw8a"/><path class="p4j9py9tw"/><path class="d0l4pqiqc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:ocean-plastic-duotone-bold" /></template>
<style>
.d0l4pqiqc {
  d: path("m3 18 3 -3 3 3 3 -3 3 3 3 -3 3 3");
}

.p4j9py9tw {
  d: path("M10.5 5V2h3v3");
}

.qm04bxb0u {
  fill: currentColor;
  d: path("M9 5v9h6V5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.vywsisw8a {
  d: path("M9 5v9h6V5Z");
}

</style>
