<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xak-ucxea"/><rect class="xiu-zs_4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:neutron-player" /></template>
<style>
.xak-ucxea {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m29.667 24l-11.334-6.5v13z");
}

.xiu-zs_4m {
  width: 39px;
  height: 26px;
  x: 4.386px;
  y: 10.876px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 5px;
  ry: 5px;
}

</style>
