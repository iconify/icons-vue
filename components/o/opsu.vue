<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c0-soac7m"/><rect transform="rotate(-15 23.866 25.507)" class="occm-8ose"/><circle class="nd_vc8yvp"/><path class="ey498_77q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:opsu" /></template>
<style>
.c0-soac7m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m21.457 3.992l7.83 8.923a1.4 1.4 0 0 0 1.217.467l11.79-1.392a1.4 1.4 0 0 1 1.368 2.106L37.595 24.3a1.4 1.4 0 0 0-.069 1.3l4.967 10.784a1.4 1.4 0 0 1-1.58 1.95l-11.58-2.616a1.4 1.4 0 0 0-1.258.338l-8.72 8.056a1.4 1.4 0 0 1-2.344-.9L15.92 31.39a1.4 1.4 0 0 0-.71-1.093L4.855 24.494a1.4 1.4 0 0 1 .13-2.507l10.907-4.69a1.4 1.4 0 0 0 .82-1.013l2.32-11.643a1.4 1.4 0 0 1 2.425-.65");
}

.ey498_77q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m27.794 17.472l2.066 7.711");
}

.nd_vc8yvp {
  cx: 30.572px;
  cy: 27.84px;
  r: 0.75px;
  fill: currentColor;
}

.occm-8ose {
  width: 6.355px;
  height: 8.42px;
  x: 20.689px;
  y: 21.297px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.177px;
}

</style>
