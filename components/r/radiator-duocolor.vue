<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="l0yu7ebpb"/><path class="t51jpabtt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:radiator-duocolor" /></template>
<style>
.l0yu7ebpb {
  stroke-opacity: 0.4;
  d: path("M3 8h16M5 16h16");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.t51jpabtt {
  d: path("M4 4a1 1 0 0 1 2 0v16a1 1 0 0 1-2 0Zm7 0a1 1 0 0 1 2 0v16a1 1 0 0 1-2 0Zm7 0a1 1 0 0 1 2 0v16a1 1 0 0 1-2 0Z");
}

</style>
