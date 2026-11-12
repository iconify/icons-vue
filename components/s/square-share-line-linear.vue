<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="scc4a1b-n"/><path class="hrauyebmu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:square-share-line-linear" /></template>
<style>
.hrauyebmu {
  stroke-linejoin: round;
  d: path("M22 7H14C12.1824 7 11.0867 7.89202 10.6804 8.30029L10.4908 8.49082L10.3003 8.68042C9.89202 9.08671 9 10.1824 9 12V15M17 12L22 7L17 2");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.scc4a1b-n {
  d: path("M22 13.9979C21.9711 17.4119 21.7815 19.294 20.5404 20.5352C19.0755 22 16.7179 22 12.0026 22C7.28733 22 4.9297 22 3.46485 20.5352C2 19.0703 2 16.7127 2 11.9974C2 7.28212 2 4.92448 3.46485 3.45963C4.70599 2.21848 6.58807 2.02895 10.0021 2");
}

</style>
