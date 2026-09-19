<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a4vj28bpa"/><path class="smwybrbam"/><path class="e471xab0g"/><path class="kavx09qyz"/><path class="w2t_ntb1h"/><ellipse transform="rotate(-3.306 31.323 28.175)" class="k6qip2bra"/><path class="zcjyiqbns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nulls-brawl" /></template>
<style>
.a4vj28bpa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.58 8.192c12.721 3.215 9.578 31.18-12.763 33.325c1.612-7.42-2.809-16.736.357-23.275c2.57-5.313 7.775-11.22 12.405-10.05");
}

.e471xab0g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.633 33.597c-3.472 6.147-5.148 9.174-7.574 9.963c-2.84.923-9.328-1.009-15.687-5.015");
}

.k6qip2bra {
  cx: 31.323px;
  cy: 28.175px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.86px;
  ry: 5.724px;
}

.kavx09qyz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.06 36.407c2.773 5.572 10.544 8.437 12.134.06c-4.1 2.272-8.112.886-12.134-.06");
}

.smwybrbam {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.92 14.008c9.265 2.958 13.451 9.78 13.713 19.59c7.956 1.005 6.742-8.158 5.35-12.912l-.986 2.241c-4.03-11.68-15.255-16.096-21.925-13.679");
}

.w2t_ntb1h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m21.682 38.697l1.171-1.613l1.046 3.566l2.418-2.988l3.28 3.42l.575-3.771m-3.567-15.729l2.57-1.285l-1.195 3.138z");
}

.zcjyiqbns {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m30.34 28.175l.18 1.91m-4.184 5.157c1.688 1.977 3.15 1.038 4.095-.15c-1.494-.175-2.826-.067-4.095.15M27.51 9.046c1.878-1.611 3.504-3.222 4.818-4.833c3.21 1.932 4.371 5.097 3.636 9.403");
}

</style>
