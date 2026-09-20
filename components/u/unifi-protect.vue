<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="b_ls79cms"/><rect class="sjoux7vsx"/><path class="v55e15zwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:unifi-protect" /></template>
<style>
.b_ls79cms {
  width: 13.123px;
  height: 14.966px;
  x: 17.439px;
  y: 7.067px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 6.561px;
}

.sjoux7vsx {
  width: 17.624px;
  height: 20.1px;
  x: 15.188px;
  y: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 8.812px;
}

.v55e15zwj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.747 15.788v24.797a2.406 2.406 0 0 1-2.023 2.375a42.5 42.5 0 0 1-13.512 0a2.406 2.406 0 0 1-2.024-2.375V15.788");
}

</style>
