<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ppa7a2bor"/><path class="s0fkxbc0m"/><ellipse class="x10fxtbdr"/><path class="yw96_eb5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:onefootball" /></template>
<style>
.ppa7a2bor {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.941 7.926C16.297 40.171 16.53 39.862 16.53 39.862M35.726 8.06L24.621 40.075");
}

.s0fkxbc0m {
  fill: none;
  stroke: currentColor;
  d: path("m16.53 39.861l8.092.213m3.319-32.148l7.785.135");
}

.x10fxtbdr {
  cx: 35.928px;
  cy: 33.403px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 6.572px;
  ry: 6.671px;
}

.yw96_eb5d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.621 8.04c0 4.589-1.577 8.37-6.225 11.63c-4.399 3.085-9.83 3.057-12.895 1.606M24.621 8.04l-6.801-.046a6.32 6.32 0 0 1-3.36 5.871a9.57 9.57 0 0 1-6.616.876m0-.001L5.5 21.277");
}

</style>
