<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<ellipse class="jb9upkbdc"/><circle class="e3u2dyzya"/><ellipse class="ti6w_9n9h"/><path class="infn3hb_n"/><path class="p92b4d0vt"/><circle class="ovyc7438b"/><path class="ai160u8le"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:silentnotes" /></template>
<style>
.ai160u8le {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.078 10.176s-.922.49-3.078.49s-3.078-.49-3.078-.49");
}

.e3u2dyzya {
  cx: 19.592px;
  cy: 24.691px;
  r: 2.014px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.infn3hb_n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.72 30.259c-.624 1.337-1.412 1.783-2.72 1.783s-2.096-.446-2.72-1.784m9.655-11.668L24 3.5l-6.935 15.09");
}

.jb9upkbdc {
  cx: 19.05px;
  cy: 23.636px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4.95px;
  ry: 5.508px;
}

.ovyc7438b {
  cx: 28.408px;
  cy: 24.691px;
  r: 2.014px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.p92b4d0vt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.613 28.277V44.5H16.387V28.277");
}

.ti6w_9n9h {
  cx: 28.95px;
  cy: 23.636px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4.95px;
  ry: 5.508px;
}

</style>
