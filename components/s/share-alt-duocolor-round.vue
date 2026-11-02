<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="j3fzuu1vw"/><path class="oc1leduhf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:share-alt-duocolor-round" /></template>
<style>
.j3fzuu1vw {
  stroke-opacity: 0.4;
  d: path("m10 11l4-3m-4 5l4 3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oc1leduhf {
  d: path("M20 8a3.162 3.162 0 1 1-6-2a3.162 3.162 0 0 1 6 2m-10 5a3.162 3.162 0 1 1-6-2a3.162 3.162 0 0 1 6 2m10 5a3.162 3.162 0 1 1-6-2a3.162 3.162 0 0 1 6 2");
}

</style>
