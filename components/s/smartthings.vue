<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="rn9-ocfze"/><circle class="de-rgmb4h"/><circle class="gkgeplb1y"/><circle class="hf9_7-c9n"/><circle class="onj8ofbyr"/><circle class="u_gvghe0r"/><path class="hzpu4sfju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:smartthings" /></template>
<style>
.de-rgmb4h {
  cx: 38.283px;
  cy: 20.695px;
  r: 4.217px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.gkgeplb1y {
  cx: 32.804px;
  cy: 37.643px;
  r: 4.217px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.hf9_7-c9n {
  cx: 15.12px;
  cy: 37.643px;
  r: 4.217px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.hzpu4sfju {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m23.864 10.357l.165 15.169m14.254-4.831l-6.03 2.044m.551 14.904l-3.522-4.862M15.12 37.643l3.79-5.155M9.717 20.967l14.312 4.559");
}

.onj8ofbyr {
  cx: 9.717px;
  cy: 20.967px;
  r: 4.217px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.rn9-ocfze {
  cx: 24.029px;
  cy: 25.526px;
  r: 5.87px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.u_gvghe0r {
  cx: 23.864px;
  cy: 10.357px;
  r: 4.217px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
