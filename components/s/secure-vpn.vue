<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xe42g1_ve"/><g class="y9tr6bcfx"><circle class="gbwa8xbdv"/><path class="xp6k6ejjd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:secure-vpn" /></template>
<style>
.gbwa8xbdv {
  cx: 18.603px;
  cy: 24px;
  r: 4.936px;
}

.xe42g1_ve {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.646 43.297h12.708c2.963 0 5.7-1.58 7.18-4.145l6.355-11.006a8.29 8.29 0 0 0 0-8.292L37.535 8.848a8.29 8.29 0 0 0-7.18-4.145h-12.71a8.29 8.29 0 0 0-7.18 4.145L4.111 19.854a8.29 8.29 0 0 0 0 8.292l6.354 11.006a8.29 8.29 0 0 0 7.18 4.145");
}

.xp6k6ejjd {
  d: path("M34.332 24.018H23.539m7.176 2.953v-2.953");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
