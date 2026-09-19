<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="vq55xdbnp"/><path class="bvtve3j2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:searchbar-ex" /></template>
<style>
.bvtve3j2j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m27.61 27.61l1.507 1.507m0 0v3.771l9.612 9.612l3.771-3.771l-9.612-9.612z");
}

.vq55xdbnp {
  cx: 18.451px;
  cy: 18.451px;
  r: 12.951px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
