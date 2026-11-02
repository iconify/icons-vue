<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="fho5bf-il"/><path class="f0t1oxrlh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:paint-roller-duocolor-sharp" /></template>
<style>
.f0t1oxrlh {
  d: path("M3 3h14v6H3Z");
}

.fho5bf-il {
  stroke-opacity: 0.4;
  d: path("M17 6h4v6h-9v3m-2 0h4v6h-4Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
