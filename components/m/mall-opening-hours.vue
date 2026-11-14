<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s8c-wpbhi"/><path class="kq2eg_b6x"/><path class="knt1fachy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mall-opening-hours" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.knt1fachy {
  d: path("M18 16v2l1.5.75");
}

.kq2eg_b6x {
  d: path("M14.25 18a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0");
}

.s8c-wpbhi {
  d: path("M12.449 21.5H3.5V10q0-.172.008-.343t.026-.343q.017-.171.042-.341t.059-.339q.033-.168.075-.335t.091-.331t.108-.326t.124-.321t.139-.314t.155-.307t.169-.299t.184-.29q.095-.143.198-.281q.102-.138.211-.271t.224-.26t.237-.249q.122-.121.249-.237t.26-.224q.133-.109.271-.211q.138-.103.281-.198t.29-.184t.299-.169t.307-.155q.155-.073.314-.139t.321-.124t.326-.108t.331-.091t.335-.075t.339-.059t.341-.042t.343-.026Q10.328 3 10.5 3t.343.008q.172.009.343.026t.341.042t.339.059q.168.033.335.075t.331.091t.326.108t.321.124t.314.139t.307.155t.299.169t.29.184t.281.198t.271.211t.26.224t.249.237t.237.249t.224.26t.211.271q.103.138.198.281t.184.29q.088.148.169.299q.081.152.155.307q.073.155.139.314t.124.321t.108.326t.091.331q.042.167.075.335q.034.169.059.339t.042.341t.026.343q.008.171.008.343v1.451m-7-.451v10.5m-1.5-5h.01");
}

</style>
