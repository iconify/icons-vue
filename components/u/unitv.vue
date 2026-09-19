<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cfx1vlbcq"/><path class="xp6yr-5ia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:unitv" /></template>
<style>
.cfx1vlbcq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.857 34.323L18.694 10.877V37.98l13.48-14.023");
}

.xp6yr-5ia {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.949 43.546c-9.593 4.392-20.955 1.174-26.82-7.595s-4.5-20.5 3.222-27.688C17.073 1.074 28.871.552 37.2 7.029s10.725 18.04 5.658 27.294");
}

</style>
