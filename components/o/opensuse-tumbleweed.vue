<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="irz6ktbyv"/><path class="t234cpgpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:opensuse-tumbleweed" /></template>
<style>
.irz6ktbyv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.75 24A9.25 9.25 0 1 1 24 14.75M33.25 24A9.25 9.25 0 1 1 24 33.25M33.25 24h-18.5M24 14.75v18.5");
}

.t234cpgpn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 14.75h9.25V5.5M42.5 33.25h-9.25v9.25");
}

</style>
