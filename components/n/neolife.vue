<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><ellipse class="fj0fjyb4y"/><ellipse transform="rotate(-60 26.971 20.573)" class="j7pn7ybxv"/><ellipse transform="rotate(-51.817 27.115 34.316)" class="srypq-aea"/><ellipse transform="rotate(-51.817 27.353 27.471)" class="alnhefbln"/><ellipse transform="rotate(-30 21.028 20.573)" class="btwbsxbsn"/><ellipse transform="rotate(-38.183 20.885 34.316)" class="sd1i9gzpp"/><ellipse transform="rotate(-38.186 20.645 27.47)" class="uka353t_m"/><path class="yvf_b6bwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:neolife" /></template>
<style>
.alnhefbln {
  cx: 27.353px;
  cy: 27.471px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4.325px;
  ry: 1.603px;
}

.btwbsxbsn {
  cx: 21.029px;
  cy: 20.573px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.512px;
  ry: 4.325px;
}

.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.fj0fjyb4y {
  cx: 24px;
  cy: 14.33px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.988px;
  ry: 4.643px;
}

.j7pn7ybxv {
  cx: 26.971px;
  cy: 20.573px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4.325px;
  ry: 1.512px;
}

.sd1i9gzpp {
  cx: 20.885px;
  cy: 34.316px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.512px;
  ry: 4.325px;
}

.srypq-aea {
  cx: 27.115px;
  cy: 34.316px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4.325px;
  ry: 1.512px;
}

.uka353t_m {
  cx: 20.647px;
  cy: 27.471px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.603px;
  ry: 4.325px;
}

.yvf_b6bwg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 18.973V45.5");
}

</style>
