<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zgjnrdblq"/><circle class="l826i2xin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:weward" /></template>
<style>
.l826i2xin {
  cx: 24.055px;
  cy: 20.469px;
  r: 2.071px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zgjnrdblq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.633 13.366C12.41 4.729-1.359 15.122 7.257 24.79l11.957 13.07l11.134-11.425c2.332-2.488 4.616-9.236-1.453-13.457c-3.204-2.003-7.336-1.634-10.262.388c-4.355 2.976-5.004 8.886-1.84 12.489L28.509 37.81l12.489-13.554c7.947-9.663-4.938-18.762-12.102-11.279");
}

</style>
