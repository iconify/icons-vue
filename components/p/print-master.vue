<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="slua27zhk"/><circle class="ilh3w3bvu"/><circle class="r3-jij9xl"/><path class="dsuc6mkci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:print-master" /></template>
<style>
.dsuc6mkci {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.097 29.657s7.728 2.589 15.769.019");
}

.ilh3w3bvu {
  cx: 35.206px;
  cy: 15.541px;
  r: 1.267px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.r3-jij9xl {
  cx: 36.987px;
  cy: 21.581px;
  r: 2.497px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.slua27zhk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.102 40.985c-9.8-.034-8.106-11.343-8.106-11.343c-8.827-.154-11.496-2.77-11.496-2.77c0-17.378 12.556-19.87 19.52-19.87c6.955 0 19.48 3.099 19.48 19.869c0 0-2.669 2.617-11.496 2.771c0 0 2.087 11.288-7.957 11.355");
}

</style>
