<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="jaohots9m"/><path class="dqmi6gbir"/><path class="dc3mvrbkm"/><path class="q0octjaid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mobile-icoca" /></template>
<style>
.dc3mvrbkm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.529 30.743c2.105-.478 2.19-1.388 1.634-1.388c-5.353 0-5.55 3.347-10.163 3.347s-4.81-3.347-10.163-3.347c-.556 0-.471.91 1.633 1.388c4.065.922 4.593 3.785 8.53 3.785s4.464-2.862 8.529-3.785");
}

.dqmi6gbir {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.468 16.582c-1.858.273-3.298.142-7.66 1.333m-17.274-1.333c1.857.273 3.297.142 7.659 1.333m11.758 11.969c-1.629-1.212-4.208-1.928-6.951-1.928c-2.74.004-5.314.72-6.938 1.933");
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

.jaohots9m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 27.651c0-9.478-8.283-17.161-18.5-17.161S5.5 18.173 5.5 27.651");
}

.q0octjaid {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 24c-6.162 0-6.847 5.355-10.163 5.355c-1.118 0-1.775-1.404-.14-1.974c3.713-1.297 4.046-8.006 10.303-8.006s6.59 6.71 10.304 8.006c1.634.57.977 1.974-.14 1.974C30.846 29.355 30.161 24 24 24m2.13-.974l.609-.487m-4.869.487l-.608-.487");
}

</style>
