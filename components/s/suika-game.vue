<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="ky85zibvp"/><g class="y9tr6bcfx"><path class="fq9lmcbrv"/><ellipse class="gq1df6bxf"/><path class="yucc_db7y"/></g><g class="y9tr6bcfx"><path class="hf209gb0c"/><path class="pl5wsbbxa"/><path class="e5e8g-bti"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:suika-game" /></template>
<style>
.e5e8g-bti {
  d: path("M36.33 17.84c8.143 1.994 11.315 5.681 7.672 8.916s-13.151 5.175-22.995 4.692C11.164 30.964 3.552 28.182 2.6 24.72s5-6.7 14.4-7.831m1.798-.186c5.407-.472 11.125-.19 15.95.784");
}

.fq9lmcbrv {
  d: path("M26.395 24.913L23.83 28.71m-2.566-3.797l2.565 3.798");
}

.gq1df6bxf {
  cx: 32.266px;
  cy: 23.172px;
  rx: 2.123px;
  ry: 2.139px;
}

.hf209gb0c {
  d: path("M11.668 9.94c9.577-5.352 22.756-3.615 29.669 3.911c6.913 7.527 5.025 18.084-4.25 23.765S14.55 42.021 7.233 34.743s-6.008-17.891 2.947-23.89");
}

.ky85zibvp {
  cx: 23.999px;
  cy: 24px;
  r: 21.499px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.pl5wsbbxa {
  d: path("M10.18 33.454C1.225 29.14-.084 21.51 7.233 16.274c7.317-5.233 20.58-6.151 29.854-2.066s11.163 11.678 4.25 17.09s-20.092 6.661-29.669 2.812");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yucc_db7y {
  d: path("m13.746 20.587l3.77 2.585m-3.77 2.585l3.77-2.585");
}

</style>
