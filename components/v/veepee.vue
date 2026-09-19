<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lgo5lybib"/><path class="h7qrwacfd"/><path class="qf0dm2bdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:veepee" /></template>
<style>
.h7qrwacfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.356 13.366s1.06-3.642 4.701-5.818c3.971 4.405 4.35 25.475-15.215 31.973");
}

.lgo5lybib {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.495 39.307c-3.63-4.475-.358-11.35 6.775-11.024C16.636 14.35 24.65 5.5 24.65 5.5c10.532 5.738 12.929 19.816 5.99 28.196c-4.057 4.901-11.509 7.48-21.977 8.804");
}

.qf0dm2bdn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.338 27.577C35.14 33.633 26.597 38.035 21.842 39.52");
}

</style>
