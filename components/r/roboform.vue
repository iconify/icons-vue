<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="ank5m11dj"/><path class="t3srpgbki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:roboform" /></template>
<style>
.ank5m11dj {
  width: 34.231px;
  height: 26.437px;
  x: 7.009px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 6.921px;
  ry: 6.921px;
}

.t3srpgbki {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.029 31.963H35.97a5.27 5.27 0 0 1 5.27 5.268h0a5.27 5.27 0 0 1-5.27 5.27H12.03a5.27 5.27 0 0 1-5.27-5.27h0a5.27 5.27 0 0 1 5.27-5.268m8.895-13.31a3.703 3.703 0 1 1 0-.026m6.525.026a3.703 3.703 0 1 0 0-.026");
}

</style>
