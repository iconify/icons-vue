<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="os9l22bpp"/><circle class="ovg3wyb5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tradingview" /></template>
<style>
.os9l22bpp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 14.453v7.82h7.365v11.274h7.82V14.453zm21.702 19.094l8.124-19.094H43.5l-8.124 19.094z");
}

.ovg3wyb5m {
  cx: 25.841px;
  cy: 18.363px;
  r: 3.91px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
