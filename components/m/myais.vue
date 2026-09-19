<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sdpg_mqhg"/><path class="d97dmkurt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:myais" /></template>
<style>
.d97dmkurt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.012 27.036c-5.351 2.096-13.245 4.397-22.215-2.909c7.66 13.021 18.777 9.169 22.215 2.91");
}

.sdpg_mqhg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M3.5 17.13c13.96 7.512 22.038 3.226 30.644 0c5.408-2.453 7.618-1.918 10.356-1.852c-4.225 2.552-9.454 5.84-11.678 7.885c-1.207 1.11-2.784 1.744-3.8 2.145C18.033 29.64 8.366 21.728 3.5 17.129Z");
}

</style>
