<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wn8i1hruc"/><path class="yjh95_brc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:save-duocolor" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.wn8i1hruc {
  stroke-opacity: 0.4;
  d: path("M9 7h6");
}

.yjh95_brc {
  d: path("M12 21H5a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2h11c.64 0 1.36.36 2 1l2 2c.64.64 1 1.36 1 2v11a2 2 0 0 1-2 2zm-5 0v-5a2 2 0 0 1 2-2h6a2 2 0 0 1 2 2v5");
}

</style>
