<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<ellipse class="rmstcabfe"/><path class="zwfis9bbz"/><path class="juhlkabmq"/><path class="sh1uzwzwu"/><ellipse class="g964fgd-g"/><path class="hzb1zabbf"/><path class="n53avtbxp"/><path class="u4jwsgszd"/><circle class="vi_nxfq0r"/><path class="u_gdwdbyd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:raiffeisen-e-banking" /></template>
<style>
.g964fgd-g {
  cx: 33.093px;
  cy: 14.608px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 10.407px;
  ry: 4.337px;
}

.hzb1zabbf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.685 14.608v4.337c0 2.396 4.66 4.338 10.408 4.338S43.5 21.34 43.5 18.945v-4.337");
}

.juhlkabmq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 19.73v4.338c0 2.395 4.66 4.337 10.407 4.337q.384 0 .761-.011");
}

.n53avtbxp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.642 27.489c4.515-.474 7.858-2.177 7.858-4.206v-4.338m-20.815.001v4.337a2.3 2.3 0 0 0 .704 1.57");
}

.rmstcabfe {
  cx: 25.942px;
  cy: 29.055px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 10.407px;
  ry: 4.337px;
}

.sh1uzwzwu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 24.068v4.337c0 2.396 4.66 4.338 10.407 4.338q.316 0 .627-.008");
}

.u_gdwdbyd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.85 42.5v-8h2.619a2.687 2.687 0 0 1 0 5.374H35.85m2.619-.001l2.619 2.625");
}

.u4jwsgszd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.35 31.74c4.152-.569 7.15-2.199 7.15-4.12v-4.337");
}

.vi_nxfq0r {
  cx: 38.5px;
  cy: 38.5px;
  r: 7px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zwfis9bbz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.349 31.837v-2.782m-20.814 0v4.337c0 2.395 4.659 4.337 10.407 4.337a22 22 0 0 0 5.716-.712M22.687 16.85a19.1 19.1 0 0 0-7.78-1.456C9.16 15.394 4.5 17.335 4.5 19.73s4.66 4.337 10.407 4.337a19.1 19.1 0 0 0 7.78-1.456");
}

</style>
