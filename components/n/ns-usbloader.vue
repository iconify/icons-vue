<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ym_x6f7ti"/><circle class="mfiooi5ro"/><circle class="q3ksyfkjs"/><circle class="dgz0p56xk"/><circle class="lbr8sfbss"/><circle class="t9iqbpblk"/><circle class="o3pcpibgk"/><circle class="escn_xeob"/><path class="x9_ctzbkz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ns-usbloader" /></template>
<style>
.dgz0p56xk {
  cx: 14.75px;
  cy: 30.596px;
  r: 1.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.escn_xeob {
  cx: 33.25px;
  cy: 33.5px;
  r: 2px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.lbr8sfbss {
  cx: 11.5px;
  cy: 27.383px;
  r: 1.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.mfiooi5ro {
  cx: 14.75px;
  cy: 14.396px;
  r: 3.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.o3pcpibgk {
  cx: 28.5px;
  cy: 21.5px;
  r: 1px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.q3ksyfkjs {
  cx: 14.75px;
  cy: 24.096px;
  r: 1.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.t9iqbpblk {
  cx: 18px;
  cy: 27.383px;
  r: 1.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.x9_ctzbkz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.25 31.5V12m-1.26 1.89L33.25 12l1.26 1.89M28.5 22.5v1.606c0 2.638 4.75 3.88 4.75 6.294M38 18.261v2.706c0 2.638-4.75 3.88-4.75 6.294m3.9-10.761h1.75v1.75h-1.75z");
}

.ym_x6f7ti {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 42.5H9.5c-2.216 0-4-1.784-4-4v-29c0-2.216 1.784-4 4-4H24m0 0h18.5v37H24z");
}

</style>
