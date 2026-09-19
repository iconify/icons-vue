<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<ellipse transform="rotate(-7 24 25.37)" class="gchmvbcfd"/><ellipse transform="rotate(-43.59 30.704 24.936)" class="oj4qggbpi"/><path class="uqpy-qd3z"/><ellipse transform="rotate(-71.81 19.624 26.448)" class="v1237-btv"/><circle class="d5civo41r"/><circle class="i3m07x9gt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:south-park-phone-destroyer" /></template>
<style>
.d5civo41r {
  cx: 28.853px;
  cy: 25.141px;
  r: 0.757px;
  fill: currentColor;
}

.gchmvbcfd {
  cx: 24px;
  cy: 25.371px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 21.053px;
  ry: 17.013px;
}

.i3m07x9gt {
  cx: 20.77px;
  cy: 25.999px;
  r: 0.75px;
  fill: currentColor;
}

.oj4qggbpi {
  cx: 30.704px;
  cy: 24.936px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4.433px;
  ry: 5.624px;
}

.uqpy-qd3z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m23.696 33.928l5.84-.426l-1.195 3.602l-2.968-.035l-3.008-1.978zM3 26.314c12.782-8.82 26.32-11.276 40.675-7.745m-28.589-8.272l.4-1.87q1.563-.495 2.49-1.644q1.424-.786 3.261-.573q.372.042.42-.619q1.599-.24 3.124.809c1.477-.304 2.394.717 2.647 1.993");
}

.v1237-btv {
  cx: 19.624px;
  cy: 26.448px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 5.624px;
  ry: 4.433px;
}

</style>
