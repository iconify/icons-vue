<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="xxu1j7xwh"/><circle class="rpddjocsb"/><circle class="qazn45b-j"/><circle class="e6m-trbuf"/><path class="hgbicz2cl"/><path class="mr04pjbsc"/><path class="r9s7h_b_z"/><rect class="hgk_oxxcm"/><rect class="wovj3nb8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:voyager-for-lemmy-psych" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.e6m-trbuf {
  cx: 19.394px;
  cy: 24.24px;
  r: 0.75px;
  fill: currentColor;
}

.hgbicz2cl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m18.832 29.967l-2.098-.827m1.761 2.58l-3.504.224m23.542-16.57c-2.327-2.72-5.44-1.402-5.44 1.682s1.683 3.589 1.683 7.29c0 4.906-3.733 10.157-9.55 11.775a4.6 4.6 0 0 1-2.452 0c-5.818-1.618-9.55-6.869-9.55-11.775c0-3.701 1.682-4.206 1.682-7.29s-3.112-4.402-5.439-1.682");
}

.hgk_oxxcm {
  width: 3.076px;
  height: 5.021px;
  x: 17.856px;
  y: 22.043px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.538px;
  ry: 1.538px;
}

.mr04pjbsc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.664 22.812c5.495-1.03 7.542-6.41 4.738-9.317c-2.3-2.383-6.365-1.906-9.224 3.309c-2.075-1.038-4-1.374-6.178-1.374m6.465 17.855c1.095 2.553 1.31 4.463 1.31 4.463c1.487.645 2.78 2.775 3.115 4.794");
}

.qazn45b-j {
  cx: 28.606px;
  cy: 24.24px;
  r: 0.75px;
  fill: currentColor;
}

.r9s7h_b_z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.927 34.498C30.457 36.645 28.551 38.7 24 38.7s-6.457-2.056-6.927-4.203m12.095-4.53l2.098-.827m-1.761 2.58l3.504.224");
}

.rpddjocsb {
  cx: 24px;
  cy: 32.224px;
  r: 2.257px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.wovj3nb8a {
  width: 3.076px;
  height: 5.021px;
  x: 27.068px;
  y: 22.043px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.538px;
  ry: 1.538px;
}

.xxu1j7xwh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.336 22.812c-5.495-1.03-7.542-6.41-4.738-9.317c2.3-2.383 6.365-1.906 9.224 3.309c2.075-1.038 4-1.374 6.178-1.374m-6.465 17.855c-1.095 2.553-1.31 4.463-1.31 4.463c-1.487.645-2.78 2.775-3.115 4.794m14.287-1.682c1.276-.14 2.538-.673 2.538-.673");
}

</style>
