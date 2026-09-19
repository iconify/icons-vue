<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><circle class="o4cp14ksx"/><path class="vw210phzt"/><path class="glpwnvbfa"/><circle class="typac8ipw"/><path class="hs8y__sxv"/><rect class="jzyw83bin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:simplygo" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.glpwnvbfa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.65 22.02v2.71c0 .91-.74 1.64-1.64 1.64h0c-.91 0-1.64-.74-1.64-1.64v-2.71m-15.6 1.62c0-.91.74-1.64 1.64-1.64h0c.91 0 1.64.74 1.64 1.64v2.71M13.77 22v4.35m3.29-2.71c0-.91.74-1.64 1.64-1.64h0c.91 0 1.64.74 1.64 1.64v2.71");
}

.hs8y__sxv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.03 22v4.35m-5.81-.72c.4.52.91.72 1.61.72h.97c.91 0 1.64-.73 1.64-1.64h0c0-.91-.73-1.65-1.64-1.65H7.73c-.91 0-1.64-.73-1.64-1.64h0c0-.91.74-1.65 1.65-1.65h.97c.7 0 1.21.2 1.61.72m16.77-.69v5.75c0 .45.37.82.82.82h.25m-5.98-1.64c0 .91.74 1.64 1.64 1.64h0c.91 0 1.64-.74 1.64-1.64v-1.07c0-.91-.74-1.64-1.64-1.64h0c-.91 0-1.64.74-1.64 1.64m0-1.64v6.57m14.83-6.62c0-1.2-.97-2.18-2.18-2.18h0c-1.2 0-2.18.97-2.18 2.18v2.22c0 1.2.97 2.18 2.18 2.18h0c1.2 0 2.18-.97 2.18-2.18h-2.18");
}

.jzyw83bin {
  width: 3.29px;
  height: 4.35px;
  x: 38.63px;
  y: 22.02px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.64px;
  ry: 1.64px;
}

.o4cp14ksx {
  cx: 43.37px;
  cy: 26.07px;
  r: 0.75px;
  fill: currentColor;
}

.typac8ipw {
  cx: 12.03px;
  cy: 19.99px;
  r: 0.58px;
  fill: currentColor;
}

.vw210phzt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.03 28.28c1.5 2.32 6.64 2.49 8.01 0m-9.39-3.55v2.22c0 .91-.74 1.64-1.64 1.64h0c-.45 0-.86-.18-1.16-.48");
}

</style>
