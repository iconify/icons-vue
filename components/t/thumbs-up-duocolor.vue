<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nwwpoi3_a"/><path class="gg2c-rbix"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:thumbs-up-duocolor" /></template>
<style>
.gg2c-rbix {
  d: path("M7 10a4 4 0 0 0 4-4V5a2 2 0 1 1 4 0v3a2 2 0 0 0 2 2h2a2 2 0 0 1 2 2v2l-2 6c-.2.597-1.005 1-2 1H9a2 2 0 0 1-2-2");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nwwpoi3_a {
  stroke-opacity: 0.4;
  d: path("M7 10H5a2 2 0 0 0-2 2v7a2 2 0 1 0 4 0z");
}

</style>
