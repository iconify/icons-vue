<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xu3z_sbsv"/><path class="aqdspczqh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pet-diabetes" /></template>
<style>
.aqdspczqh {
  d: path("M15 16a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0Zm2.75-1.25a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0ZM20.5 16a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xu3z_sbsv {
  d: path("M17.216 11.395C15.389 7.203 11 2.5 11 2.5s-7 7.5-7 12q0 .172.008.343t.026.343q.017.171.042.341t.059.339q.033.168.075.335t.091.331t.108.326t.124.321t.139.314t.155.307t.169.299t.184.29q.095.143.198.281q.102.138.211.271t.224.26t.237.249t.249.237t.26.224t.271.211q.138.103.281.198t.29.184q.148.088.299.169q.152.081.307.155q.155.073.314.139t.321.124t.326.108t.331.091q.167.042.335.075q.169.034.339.059t.341.042t.343.026q.171.008.343.008q1.266 0 2.451-.443M16 19.5a2.5 2 0 1 0 5 0a2.5 2 0 1 0-5 0Z");
}

</style>
