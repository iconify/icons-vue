<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z5t1rccst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:vectormotion" /></template>
<style>
.z5t1rccst {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.715 37.949a5.212 5.212 0 0 1-9.448 0L5.587 8.612a.907.907 0 0 1 1.102-1.247l.946.307a4.8 4.8 0 0 1 2.865 2.533l10.004 21.454a.972.972 0 0 0 1.762 0l9.98-21.401a3.94 3.94 0 0 1 2.939-2.223l6.033-.979a1.104 1.104 0 0 1 1.177 1.556z");
}

</style>
