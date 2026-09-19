<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="zlldudb7w"/><circle class="rf2p8bhit"/><path class="tm0h52b4k"/><circle class="l6c5rccqb"/><path class="zqxrgjbrz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:toeslagen" /></template>
<style>
.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.l6c5rccqb {
  cx: 25.914px;
  cy: 13.196px;
  r: 1.374px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.rf2p8bhit {
  cx: 21.876px;
  cy: 13.196px;
  r: 1.374px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.tm0h52b4k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m22.081 14.552l.076 1.644m1.738 17.215c6.336 0 9.87-1.934 9.87-4.626s-.646-5.103-1.936-8.019c.898-1.962.393-4.57-7.934-4.57s-8.832 2.608-7.935 4.57c-1.29 2.916-1.934 5.327-1.934 8.019s3.532 4.626 9.869 4.626");
}

.zlldudb7w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.841 38.9s1.409.504 4.879.504s5.993-.61 5.993-2.229s-1.43-1.367-5.846-1.43s-9.139-1.293-11.519 0c-1.974 1.073-3.185 2.103-6.848 2.187m24.213-.757c2.27-.82 5.656-2.187 7.36-2.88s3.196.041 3.7 1.114C36.61 38.31 30.028 42.5 30.028 42.5M23.25 19.252c-5.3.309-7.29 1.514-7.29 1.514");
}

.zqxrgjbrz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m25.709 14.552l-.076 1.644m.481 12.686a2.68 2.68 0 0 1-2.054.956h0a2.683 2.683 0 0 1-2.682-2.683v-2.634a2.683 2.683 0 0 1 2.682-2.683h0c.83 0 1.57.376 2.062.967m-5.744 2.061h3m-3 1.963h3");
}

</style>
