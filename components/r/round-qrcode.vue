<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eljgkkcag"/><path class="mjmyqtb8h"/><path class="h47meptjv"/><path class="wvk2fvb5k"/><path class="w3p1adcsj"/><path class="xhw1bue_m"/><path class="i3ah_iwyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-qrcode" /></template>
<style>
.eljgkkcag {
  fill: currentColor;
  d: path("M2 1h8a1 1 0 0 1 1 1v8a1 1 0 0 1-1 1H2a1 1 0 0 1-1-1V2a1 1 0 0 1 1-1m1 2v6h6V3z");
}

.h47meptjv {
  fill: currentColor;
  d: path("M14 1h8a1 1 0 0 1 1 1v8a1 1 0 0 1-1 1h-8a1 1 0 0 1-1-1V2a1 1 0 0 1 1-1m1 2v6h6V3z");
}

.i3ah_iwyz {
  fill: currentColor;
  d: path("M23 19h-4v4h-5a1 1 0 0 1-1-1v-8v5h2v2h2v-6h-2v-2h-1h3v2h2v2h2v-4h1a1 1 0 0 1 1 1zm0 2v1a1 1 0 0 1-1 1h-1v-2z");
}

.mjmyqtb8h {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5 5h2v2H5z");
}

.w3p1adcsj {
  fill: currentColor;
  d: path("M2 13h8a1 1 0 0 1 1 1v8a1 1 0 0 1-1 1H2a1 1 0 0 1-1-1v-8a1 1 0 0 1 1-1m1 2v6h6v-6z");
}

.wvk2fvb5k {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17 5h2v2h-2z");
}

.xhw1bue_m {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5 17h2v2H5z");
}

</style>
