<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="n1r5m8bbm"/><path class="cxwdbyb2i"/><circle class="ut6j77bdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tineco" /></template>
<style>
.cxwdbyb2i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.47 27.5h-4.848c-.831 0-1.5-.669-1.5-1.5v-2c0-.831.669-1.5 1.5-1.5h4.848m-8.379 5h-5c-.83 0-1.5-.669-1.5-1.5v-2c0-.831.67-1.5 1.5-1.5h3.5c.831 0 1.5.669 1.5 1.5v1h-6.5m-8.53 2.5V24c0-.831.669-1.5 1.5-1.5h3.5c.831 0 1.5.669 1.5 1.5v3.5M6.058 19.492A18.5 18.5 0 0 1 24 5.5a18.5 18.5 0 0 1 17.945 14.001m-.283 10.005A18.5 18.5 0 0 1 24 42.5A18.5 18.5 0 0 1 6.338 29.506M9 22.5H2.5m3.25 0v5m5.28-5v5");
}

.n1r5m8bbm {
  width: 7px;
  height: 5px;
  x: 38.5px;
  y: 22.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.5px;
  ry: 1.5px;
}

.ut6j77bdm {
  cx: 5.75px;
  cy: 21px;
  r: 0.5px;
  fill: currentColor;
}

</style>
