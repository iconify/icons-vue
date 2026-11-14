<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fs3vc7bfb"/><path class="hn8ja4bqc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:waypoint-add" /></template>
<style>
.fs3vc7bfb {
  d: path("M12.237 19.218A84 84 0 0 1 10.5 21c-4-4-7-7.5-7-11.5q0-.172.008-.343t.026-.343q.017-.171.042-.341t.059-.339q.033-.168.075-.335t.091-.331t.108-.326t.124-.321t.139-.314t.155-.307q.081-.151.169-.299q.088-.147.184-.29q.095-.143.198-.281q.102-.138.211-.271t.224-.26t.237-.249t.249-.237t.26-.224t.271-.211q.138-.103.281-.198t.29-.184q.148-.088.299-.169q.152-.081.307-.155q.155-.073.314-.139t.321-.124t.326-.108t.331-.091t.335-.075t.339-.059t.341-.042t.343-.026q.171-.008.343-.008t.343.008q.172.009.343.026t.341.042t.339.059q.168.033.335.075t.331.091t.326.108t.321.124t.314.139t.307.155t.299.169t.29.184t.281.198t.271.211t.26.224t.249.237t.237.249t.224.26t.211.271q.103.138.198.281t.184.29q.088.148.169.299q.081.152.155.307q.073.155.139.314t.124.321t.108.326t.091.331q.042.167.075.335q.034.169.059.339t.042.341t.026.343q.008.171.008.343a8.5 8.5 0 0 1-.465 2.733");
}

.hn8ja4bqc {
  d: path("M8 9.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0ZM18 15v6m-3-3h6");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
