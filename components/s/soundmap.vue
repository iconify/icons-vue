<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kf8ba7uzv"/><path class="klolfzp2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:soundmap" /></template>
<style>
.kf8ba7uzv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.352 38.048L5.5 41.229V9.952l9.852-3.181zm27.148 0l-9.852 3.181V9.952L42.5 6.771z");
}

.klolfzp2n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m32.648 41.229l-17.296-3.181V6.771l17.296 3.181z");
}

</style>
