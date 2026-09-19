<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pey5fka3c"/><path class="vm08pvb_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:vacation-days" /></template>
<style>
.pey5fka3c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.287 42.03a21.54 21.54 0 0 1 30.167-30.698m0 0L11.287 42.031");
}

.vm08pvb_r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.662 33.508C2.642 10.55 12.786 2.656 33.38 19.548m-3.728 9.834L42.5 42.2");
}

</style>
