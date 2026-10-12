<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ax--7rbmu"/><path class="u6qr_5ihc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:vulcan-salute" /></template>
<style>
.ax--7rbmu {
  d: path("m7.69 20.13l-.63-1.26q-.56-1.12-1.47-1.97l-1.93-1.8q-.91-.85-.27-1.92l.22-.36q.64-1.07 1.6-.27l1.08.9q.96.8.55-.38L4.41 6.18Q4 5 5.17 4.55l2.16-.85q1.17-.45 1.63.71l2.58 6.43q.46 1.16.92 0l2.58-6.43q.46-1.16 1.63-.71l2.16.85q1.17.45.93 1.68l-1.77 9.04q-.24 1.23-.73 2.38l-1.02 2.45q-.49 1.15-1.74 1.15h-5q-1.25 0-1.81-1.12");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.u6qr_5ihc {
  d: path("M9.5 16.75c1.5.75 3.25.75 5 0");
}

</style>
