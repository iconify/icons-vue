<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><circle class="l7hkabb-p"/><circle class="hja988r9f"/><path class="zjbeblbjc"/><rect class="afpqeqb0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:oeamtc" /></template>
<style>
.afpqeqb0q {
  width: 4.086px;
  height: 6.168px;
  x: 9.6px;
  y: 32.175px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.043px;
  ry: 2.043px;
}

.hja988r9f {
  cx: 10.583px;
  cy: 30.229px;
  r: 0.75px;
  fill: currentColor;
}

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

.l7hkabb-p {
  cx: 12.704px;
  cy: 30.229px;
  r: 0.75px;
  fill: currentColor;
}

.zjbeblbjc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.657 36.3h-2.734m-.676 2.043l2.044-6.168l2.043 6.168m1.811-.007v-6.161l3.085 6.168l3.083-6.158v6.158m1.75-6.168h4.086m-2.043 6.168v-6.168m7.337 4.101v.024a2.043 2.043 0 1 1-4.087 0v-2.082a2.044 2.044 0 0 1 4.087 0v.026");
}

</style>
