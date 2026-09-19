<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="w5r6mrimk"/><path class="htuj38dzi"/><circle class="f_g4e02cy"/><circle class="lp7qnbc4o"/><circle class="coq293o_t"/><circle class="ta75efb-v"/><path class="r1y2vlb1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tape" /></template>
<style>
.coq293o_t {
  cx: 33.926px;
  cy: 11.378px;
  r: 1.75px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.f_g4e02cy {
  cx: 27.339px;
  cy: 21.035px;
  r: 0.75px;
  fill: currentColor;
}

.htuj38dzi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.627 16.448c2.054 4.467 1.963 10.861-2.06 14.606c-1.963 1.828-8.404 1.54-8.114-5.805c.143-3.626 3.14-6.29 6.616-9.706c1.93-1.896 2.822-.694 3.558.905");
}

.lp7qnbc4o {
  cx: 10.459px;
  cy: 19.038px;
  r: 1.75px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.r1y2vlb1z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m18.28 10.3l-1.344 1.754l-.23-2.19l-1.775-1.33l2.216-.225l1.345-1.753l.229 2.189l1.776 1.33Z");
}

.ta75efb-v {
  cx: 39.176px;
  cy: 18.141px;
  r: 1.25px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.w5r6mrimk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.689 40.478a23.7 23.7 0 0 1 4.94-8.641c.988-1.081 1.877-.647 2.924-.784c3.282-.428 6.47-1.726 7.678-5.493c.608-1.898-.838-5.998-1.56-5.898a19.2 19.2 0 0 1-5.743.28a1.97 1.97 0 0 1-1.56-1.123a6.95 6.95 0 0 0-7.115-3.495");
}

</style>
