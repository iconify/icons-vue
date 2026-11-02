<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n7ra84brq"/><path class="uf7ef_qpg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:taxi-duocolor" /></template>
<style>
.n7ra84brq {
  stroke-opacity: 0.4;
  d: path("M12 18H6a2 2 0 0 1-2-2v-4l1-2c.613-1.226 1.387-2 2-2h10c.613 0 1.387.774 2 2l1 2v4a2 2 0 0 1-2 2zm-6 0h2v2H6Zm10 0h2v2h-2ZM3 12h18");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.uf7ef_qpg {
  d: path("M10 5h4M8 15h.01M16 15h.01");
}

</style>
