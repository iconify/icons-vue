<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="nol19vq4t"/><path class="r5rugytbx"/><path class="g_br6ebte"/><path class="qbunz8cnn"/><path class="vhte9_bca"/><path class="lfowyvbbt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:user-id-broken" /></template>
<style>
.g_br6ebte {
  d: path("M22 12C22 15.7712 22 17.6569 20.8284 18.8284C19.6569 20 17.7712 20 14 20H10C6.22876 20 4.34315 20 3.17157 18.8284C2 17.6569 2 15.7712 2 12C2 8.22876 2 6.34315 3.17157 5.17157C4.34315 4 6.22876 4 10 4H14C17.7712 4 19.6569 4 20.8284 5.17157C21.298 5.64118 21.5794 6.2255 21.748 7");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lfowyvbbt {
  d: path("M19 15H16");
}

.nol19vq4t {
  cx: 9px;
  cy: 9px;
  r: 2px;
}

.qbunz8cnn {
  d: path("M19 12H15");
}

.r5rugytbx {
  d: path("M13 15C13 16.1046 13 17 9 17C5 17 5 16.1046 5 15C5 13.8954 6.79086 13 9 13C11.2091 13 13 13.8954 13 15Z");
}

.vhte9_bca {
  d: path("M19 9H14");
}

</style>
