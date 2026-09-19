<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="ndrfz8b2k"/><ellipse transform="rotate(-60 34.533 9.685)" class="tx1bjvb9a"/><path class="yq4i_pfer"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mixological" /></template>
<style>
.ndrfz8b2k {
  d: path("m37.87 5.5l-1.696 2.15m-3.257 4.13l-.716.907l-10.116 12.826");
}

.tx1bjvb9a {
  cx: 34.533px;
  cy: 9.685px;
  rx: 2.594px;
  ry: 3.118px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yq4i_pfer {
  d: path("M7.944 14.209h32.112L25.451 28.84l-.29 11.34l5.416 2.319H17.52l5.32-2.319l-.194-11.34z");
}

</style>
