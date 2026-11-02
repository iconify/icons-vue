<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="dhb0b5b7w"/><path class="by2h4_pqz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:wind-turbine-duocolor-round" /></template>
<style>
.by2h4_pqz {
  d: path("M10 10a2 2 0 1 0 4 0a2 2 0 0 0-4 0m2 2v9m-4 0h8");
}

.dhb0b5b7w {
  stroke-opacity: 0.4;
  d: path("M12 8V3c1.5 1 2 3 1.41 5.59Zm1.732 3l4.33 2.5c-1.616.799-3.598.232-5.546-1.574Zm-3.464 0l-4.33 2.5c.116-1.799 1.598-3.232 4.136-4.016Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
