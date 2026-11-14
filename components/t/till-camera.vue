<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="t_lfmrpgu"/><path class="zuv_lhbly"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:till-camera" /></template>
<style>
.t_lfmrpgu {
  d: path("M2.5 3h19M5 3v2q0 .172.008.343t.026.343t.042.341q.025.17.059.339q.033.168.075.335t.091.331t.108.326t.124.321t.139.314t.155.307q.081.151.169.299q.088.147.184.29q.095.143.198.281q.102.138.211.271t.224.26t.237.249q.122.121.249.237t.26.224t.271.211t.281.198t.29.184q.148.088.299.169q.152.081.307.155q.155.073.314.139t.321.124t.326.108t.331.091t.335.075t.339.059t.341.042t.343.026Q11.828 12 12 12q.825 0 1.626-.192q.802-.191 1.538-.564m2.459-2.075q.334-.45.591-.946q.258-.497.433-1.028t.264-1.083Q19 5.559 19 5V3M5 5h14");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zuv_lhbly {
  d: path("M10 8.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm4 7.5h8v5.75h-8ZM14 19h8m-4-3.25v-3.5l.75-.5l.75.5l.75-.5l.75.5v3.5m-5 1.5h.01");
}

</style>
