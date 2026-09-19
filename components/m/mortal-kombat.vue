<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ke5oue2zp"/><path class="cubgh0bvv"/><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mortal-kombat" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.cubgh0bvv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27 23.334L34.8 12l-1-1h7.3l-1.9 1l-7.4 11.1l8.9 14.3h-4.6l-6.5-11.3l-2.6 3.467");
}

.ke5oue2zp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m7.1 37.3l1.7-1.6v-23L6.9 11h5.5l5.4 15.6L23 11h5.4L27 12.6v23l1.7 1.7H21l1.8-1.7V23.5l-5 13.9l-5.1-13.9v12.2l1.7 1.7H7.2");
}

</style>
