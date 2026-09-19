<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="nnofhsb3z"/><path class="x-iqdu7gi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:vouchervault" /></template>
<style>
.nnofhsb3z {
  cx: 24px;
  cy: 24px;
  r: 7.323px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.x-iqdu7gi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.458 16.831v-4.008A1.7 1.7 0 0 1 24 11.28a1.735 1.735 0 0 1 1.542 1.542v4.008m5.704 5.705h4.008a1.7 1.7 0 0 1 1.542 1.542a1.734 1.734 0 0 1-1.542 1.542h-4.008m-14.492-3.084h-4.008a1.7 1.7 0 0 0-1.542 1.542a1.734 1.734 0 0 0 1.542 1.542h4.008m5.704 5.704v4.008A1.7 1.7 0 0 0 24 36.873a1.734 1.734 0 0 0 1.542-1.542v-4.008m2.491-13.46l2.835-2.834a1.7 1.7 0 0 1 2.18 0a1.734 1.734 0 0 1 0 2.18l-2.834 2.834m0 8.067l2.834 2.835a1.7 1.7 0 0 1 0 2.18a1.734 1.734 0 0 1-2.18 0l-2.834-2.834m-8.067-12.428l-2.835-2.834a1.7 1.7 0 0 0-2.18 0a1.734 1.734 0 0 0 0 2.18l2.835 2.834m-.001 8.067l-2.834 2.835a1.7 1.7 0 0 0 0 2.18a1.734 1.734 0 0 0 2.18 0l2.834-2.834M15.135 14.75L8.738 5.5m24.127 9.25l6.398-9.25M42.5 18.219l-9.046 13.9m-.862 1.324L26.698 42.5m-5.396 0l-5.93-9.113m-.815-1.251L5.5 18.219");
}

</style>
