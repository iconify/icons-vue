<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="rmfg5mk6q"/><path class="w1e4r9boe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:scribble-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.rmfg5mk6q {
  d: path("M216 56v144a16 16 0 0 1-16 16H56a16 16 0 0 1-16-16V56a16 16 0 0 1 16-16h144a16 16 0 0 1 16 16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.w1e4r9boe {
  d: path("M205.67 189.66a14.61 14.61 0 0 0 0 20.68a8 8 0 0 1-11.32 11.32a30.64 30.64 0 0 1 0-43.32l9.38-9.37A14.63 14.63 0 0 0 183 148.28L116.28 215A30.63 30.63 0 0 1 73 171.72L171.72 73A14.63 14.63 0 0 0 151 52.28L84.28 119A30.63 30.63 0 0 1 41 75.72l41.34-41.38a8 8 0 0 1 11.31 11.32L52.27 87A14.63 14.63 0 0 0 73 107.72L139.72 41A30.63 30.63 0 0 1 183 84.28L84.28 183A14.63 14.63 0 0 0 105 203.72L171.72 137A30.63 30.63 0 0 1 215 180.28Z");
}

</style>
