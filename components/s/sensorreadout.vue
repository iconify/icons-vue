<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ytbawpbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sensorreadout" /></template>
<style>
.ytbawpbeo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 4.5a13.6 13.6 0 0 0 0 27.19h0A13.6 13.6 0 0 0 24 4.5m0 7.7a5.93 5.93 0 1 0 5.93 5.93A5.94 5.94 0 0 0 24 12.2m9.74 25.73L36.11 42h-4.72Zm0 0l2.37-4.09h-4.72Zm3.85 0H10.36");
}

</style>
