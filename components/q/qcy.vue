<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="apx4f8big"/><ellipse transform="rotate(-67.923 9.794 24)" class="qxoe54bee"/><ellipse transform="rotate(-67.923 23.982 24)" class="ngun43uds"/><ellipse transform="rotate(-67.923 38.206 24)" class="ei54gv21l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:qcy" /></template>
<style>
.apx4f8big {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.294 20.109L38.764 24l-2.529-3.891m2.529 7.782V24M26.64 25.286za2.647 2.647 0 0 1-2.658 2.658c-1.477 0-2.658-1.182-2.658-2.56v-2.658c0-1.476 1.181-2.658 2.658-2.56a2.54 2.54 0 0 1 2.56 2.56M12.32 27.891l-2.529-2.626m-.001 2.626za2.51 2.51 0 0 1-2.529-2.53v-2.626c0-1.459 1.168-2.626 2.53-2.626c1.459 0 2.53 1.167 2.53 2.626v2.53c0 1.459-1.07 2.626-2.53 2.626");
}

.ei54gv21l {
  cx: 38.206px;
  cy: 24px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 8.529px;
  ry: 5.844px;
}

.ngun43uds {
  cx: 23.982px;
  cy: 24px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 8.529px;
  ry: 5.844px;
}

.qxoe54bee {
  cx: 9.794px;
  cy: 24px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 8.529px;
  ry: 5.844px;
}

</style>
