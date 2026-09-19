<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vy-mwmbvm"/><circle class="lnpw39b2c"/><circle class="xz75kjq5l"/><circle class="aqkiwkb_d"/><circle class="rch0s4bmn"/><path class="f14_nwbkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-settings-input-svideo" /></template>
<style>
.aqkiwkb_d {
  cx: 9px;
  cy: 16px;
  r: 1.5px;
  fill: currentColor;
}

.f14_nwbkm {
  fill: currentColor;
  d: path("M15 7.5c0-.83-.67-1.5-1.5-1.5h-3C9.67 6 9 6.67 9 7.5S9.67 9 10.5 9h3c.83 0 1.5-.67 1.5-1.5");
}

.lnpw39b2c {
  cx: 7.5px;
  cy: 11.5px;
  r: 1.5px;
  fill: currentColor;
}

.rch0s4bmn {
  cx: 15px;
  cy: 16px;
  r: 1.5px;
  fill: currentColor;
}

.vy-mwmbvm {
  fill: currentColor;
  d: path("M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10s10-4.48 10-10S17.52 2 12 2m0 18c-4.42 0-8-3.58-8-8s3.58-8 8-8s8 3.58 8 8s-3.58 8-8 8");
}

.xz75kjq5l {
  cx: 16.5px;
  cy: 11.5px;
  r: 1.5px;
  fill: currentColor;
}

</style>
