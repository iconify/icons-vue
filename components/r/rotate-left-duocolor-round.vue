<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="gqbh24_yz"/><path class="uv591sb9m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:rotate-left-duocolor-round" /></template>
<style>
.gqbh24_yz {
  stroke-opacity: 0.4;
  d: path("M12 6h3a4 4 0 0 1 4 4m-4-7l-3 3l3 3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.uv591sb9m {
  d: path("M19 14v2a4 4 0 0 1-4 4H9a4 4 0 0 1-4-4V9a3 3 0 0 1 3-3");
}

</style>
