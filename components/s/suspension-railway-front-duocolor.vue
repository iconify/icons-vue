<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jyr9_ub8c"/><path class="bs24_olvf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:suspension-railway-front-duocolor" /></template>
<style>
.bs24_olvf {
  d: path("M12 9h5a2 2 0 0 1 2 2v7a2 2 0 0 1-2 2H7a2 2 0 0 1-2-2v-7a2 2 0 0 1 2-2zm-7 5h14");
}

.jyr9_ub8c {
  stroke-opacity: 0.4;
  d: path("M3 4h18M9 4v5m6-5v5m-6 8h.01M15 17h.01");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
