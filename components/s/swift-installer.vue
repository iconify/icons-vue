<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect transform="rotate(-44.938 26.798 25.135)" class="xqye_bcbu"/><path class="vb_zh3twj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:swift-installer" /></template>
<style>
.vb_zh3twj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24.366 10.445l4.867-4.857m-5 22.107l5.13-5.12m-2.684 7.57l5.13-5.119m-10.021.218l5.13-5.119M13.88 38.222c0-2.314-4.19-8.833-4.19-8.833S5.5 35.908 5.5 38.222a4.19 4.19 0 1 0 8.38 0");
}

.xqye_bcbu {
  width: 24.233px;
  height: 24.233px;
  x: 14.682px;
  y: 13.018px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.462px;
}

</style>
