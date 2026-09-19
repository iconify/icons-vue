<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z2n0uyb-o"/><circle class="vi_nxfq0r"/><path class="u_gdwdbyd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:raiffeisen-vorsorgeradar" /></template>
<style>
.u_gdwdbyd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.85 42.5v-8h2.619a2.687 2.687 0 0 1 0 5.374H35.85m2.619-.001l2.619 2.625");
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

.z2n0uyb-o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.824 36.934A21.504 21.504 0 0 1 21 2.708m12.431 40.619a21.52 21.52 0 0 1-24.634-4.124M24 2.5a21.51 21.51 0 0 1 19.326 30.932");
}

</style>
