<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="inm4abupt"/><path class="s1oi0eb9o"/><circle class="u6lvtdb7n"/><path class="nhdk7ibqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:smsscheduler" /></template>
<style>
.inm4abupt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m22.383 28.274l4.223 4.214a3.62 3.62 0 0 0 5.123.002l.001-.002l8.04-8.04");
}

.nhdk7ibqt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.763 13.485a3.448 3.448 0 0 1 5.151-4.586h0m9.55.186a3.445 3.445 0 1 1 4.886 4.788m-9.568-1.528v7.103l3.976 3.384m18.853 15.037l-7.253-5.946m-13.562 5.946l7.254-5.946");
}

.s1oi0eb9o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.101 22.054a11.03 11.03 0 0 1-10.575 7.916a11 11 0 0 1-.636-.044v9.277c0 .585.474 1.06 1.06 1.06h24.49a1.06 1.06 0 0 0 1.06-1.06h0v-16.08a1.06 1.06 0 0 0-1.06-1.06H27.1z");
}

.u6lvtdb7n {
  cx: 16.526px;
  cy: 18.945px;
  r: 11.026px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
