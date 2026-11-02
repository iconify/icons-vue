<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="juxszpb4t"/><path class="aswmuxbwh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:police-car-duotone-sharp" /></template>
<style>
.aswmuxbwh {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M11 8V6h2v2m-2 0h2M7 5h1m8 0h1M8 15h.01M16 15h.01M4 18v-6l2-4h12l2 4v6zm2 0h2v2H6Zm10 0h2v2h-2ZM3 12h18");
}

.ft5dv1b6b {
  fill: none;
}

.juxszpb4t {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M3 12c0-.155.036-.308.106-.447l2-4A1 1 0 0 1 6 7h12c.379 0 .725.214.894.553l2 4c.07.139.106.292.106.447v6a1 1 0 0 1-1 1h-1v1a1 1 0 0 1-1 1h-2a1 1 0 0 1-1-1v-1H9v1a1 1 0 0 1-1 1H6a1 1 0 0 1-1-1v-1H4a1 1 0 0 1-1-1Z");
}

</style>
