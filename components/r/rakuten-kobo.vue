<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="v1veeab9t"/><rect class="pjnyh1bmc"/><rect class="vqt_7o81o"/><path class="yyjwed71b"/><circle class="upxwd5bwx"/><path class="oqfmtu78s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:rakuten-kobo" /></template>
<style>
.oqfmtu78s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.35 41v-8h2.619c1.48 0 2.681 1.203 2.681 2.687s-1.2 2.686-2.681 2.686H34.35m2.62 0l2.62 2.625");
}

.pjnyh1bmc {
  width: 5.435px;
  height: 7.202px;
  x: 31.565px;
  y: 18.841px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.717px;
  ry: 2.717px;
}

.upxwd5bwx {
  cx: 37px;
  cy: 37px;
  r: 7px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.v1veeab9t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41 31.26V8a4 4 0 0 0-4-4H8a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h23.299");
}

.vqt_7o81o {
  width: 5.435px;
  height: 7.202px;
  x: 15.422px;
  y: 18.841px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.717px;
  ry: 2.717px;
}

.yyjwed71b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8 15.173v10.87m.001-2.309l4.92-4.896m-3.354 3.337l3.868 3.851m10.015-4.467a2.717 2.717 0 1 1 5.435 0v1.766a2.717 2.717 0 1 1-5.435 0m0 2.718v-10.87");
}

</style>
