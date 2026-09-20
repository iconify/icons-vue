<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qctasytjv"/><path class="iyb_7zbyq"/><circle class="zbn56sbec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:myuca" /></template>
<style>
.iyb_7zbyq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.482 24a6.485 6.485 0 0 1-11.795 3.718a6.48 6.48 0 0 1 .167-7.664a6.485 6.485 0 0 1 7.362-2.145m4.299 6.076c0-3.572 2.903-6.468 6.484-6.468s6.484 2.896 6.484 6.468m-38.969.032L4.5 17.5m38.983 6.485l.016 6.516");
}

.qctasytjv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.482 24.017a6.47 6.47 0 0 1-3.242 5.601a6.5 6.5 0 0 1-6.484 0a6.47 6.47 0 0 1-3.242-5.601");
}

.zbn56sbec {
  cx: 36.999px;
  cy: 24.001px;
  r: 0.75px;
  fill: currentColor;
}

</style>
