<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="q1_k8mb5w"/><ellipse transform="rotate(-7 23.982 24.42)" class="g_td0m2ah"/><path class="jjj8pj1wy"/><path class="ojm7mdo2m"/><path class="wtphfcb8i"/><circle class="rslvvx-yx"/><circle class="crbhhhbsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:south-park-phone-destroyer-alt-3" /></template>
<style>
.crbhhhbsc {
  cx: 26.958px;
  cy: 23.157px;
  r: 0.75px;
  fill: currentColor;
}

.g_td0m2ah {
  cx: 23.982px;
  cy: 24.419px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 13.9px;
  ry: 11.975px;
}

.jjj8pj1wy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.936 12.614c-10.449 8.985-9.163 16.709 3.949 23.479c10.369-10.047 9.083-17.775-3.95-23.488");
}

.ojm7mdo2m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.706 18.427c3.703-.805 6.23.514 7 4.364c.628 3.152-1.043 5.957-5.533 7.945");
}

.q1_k8mb5w {
  cx: 24px;
  cy: 24px;
  r: 21.498px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.rslvvx-yx {
  cx: 20.584px;
  cy: 24.735px;
  r: 0.75px;
  fill: currentColor;
}

.wtphfcb8i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.592 28.752c-4.166-.024-7.555-2.22-7.974-6.62c-.354-3.717 1.516-5.64 4.865-5.746m-1.05 19.548c-.273.839-.45 1.879-.48 2.76a21 21 0 0 1-.353 3.027m1.591-5.997c.46.386.671.785.784 1.33q.39 1.872.533 3.764q.417 1.013.95 1.557");
}

</style>
