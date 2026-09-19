<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="w_az26c9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ovinfo" /></template>
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

.w_az26c9b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 18.776h37m-21.79-3.393V11.91c.032-.304.17-1.56.302-2.213c.014-.152.058-.3.13-.434a1.2 1.2 0 0 1 .55-.411q.587-.267 1.222-.374A6 6 0 0 1 24 8.388q.544-.002 1.08.09a5 5 0 0 1 1.221.375c.22.08.412.223.552.411q.107.204.13.434c.13.644.269 1.909.308 2.213v3.472zm-.001-3.472h6.582m-5.511 3.472v.89m4.44-.89v.89");
}

</style>
