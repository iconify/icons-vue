<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="to-5kdesz"><ellipse class="yeqjlc_fk"/><circle class="b834a23pj"/><ellipse class="pq6q62zty"/><path class="i7vwu5g6r"/><ellipse class="iqmaq6bvy"/><path class="s3cb3lb5d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:medgemak" /></template>
<style>
.b834a23pj {
  cx: 38.675px;
  cy: 19.992px;
  r: 4.825px;
}

.i7vwu5g6r {
  d: path("M37.792 24.788c.2 5.514-2.574 10.73-7.313 13.753s-10.757 3.415-15.867 1.033m4.302-29.225c6.364-1.035 12.769 1.613 16.314 6.745M7.13 31.801c-2.435-5.003-1.753-10.857 1.777-15.247");
}

.iqmaq6bvy {
  cx: 26.098px;
  cy: 23.002px;
  rx: 4.962px;
  ry: 6.133px;
}

.pq6q62zty {
  cx: 10.129px;
  cy: 36.074px;
  rx: 5.629px;
  ry: 5.428px;
}

.s3cb3lb5d {
  stroke-linecap: round;
  d: path("M24 28.554c-1.778 1.038-5.402 7.706-5.246 12.32m9.88-12.607c1.813.923 4.478 4.959 5.217 7.4");
}

.to-5kdesz {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
}

.yeqjlc_fk {
  cx: 13.162px;
  cy: 12.322px;
  rx: 5.99px;
  ry: 5.824px;
}

</style>
