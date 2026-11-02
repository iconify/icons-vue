<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="gxrw_4yjw"/><path class="sdzlwabve"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:thumbs-down-duocolor-round" /></template>
<style>
.gxrw_4yjw {
  stroke-opacity: 0.4;
  d: path("M7 14H5a2 2 0 0 1-2-2V5a2 2 0 1 1 4 0z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.sdzlwabve {
  d: path("M7 14a4 4 0 0 1 4 4v1a2 2 0 1 0 4 0v-3a2 2 0 0 1 2-2h1a3 3 0 0 0 3-3v-1l-1-5c-.233-1.163-1.488-2-3-2H9a2 2 0 0 0-2 2");
}

</style>
