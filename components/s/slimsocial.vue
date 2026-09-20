<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="jb2cadbja"/><circle class="mh1ybmjlp"/><path class="r816-nb5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:slimsocial" /></template>
<style>
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

.jb2cadbja {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.333 5.5v33.795L24 35.555M12.667 5.5v33.794L24 35.554");
}

.mh1ybmjlp {
  cx: 24px;
  cy: 24px;
  r: 7.964px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.r816-nb5e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.355 26.203c.365.307.76.447 1.645.447h.449c.73 0 1.322-.593 1.322-1.325S25.179 24 24.449 24h-.898c-.73 0-1.322-.593-1.322-1.325s.592-1.325 1.322-1.325H24c.885 0 1.28.14 1.645.447");
}

</style>
