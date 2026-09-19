<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dc-a4y5vc"/><path class="cqoi8eo3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:thanh-nien" /></template>
<style>
.cqoi8eo3w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 14.236l.835 1.692l1.867.271l-1.351 1.317l.319 1.86l-1.67-.879l-1.67.878l.32-1.86l-1.351-1.316l1.867-.271zM8.789 34.278h5.447M11.513 42.5v-8.222m5.601 8.222v-8.222L22.56 42.5v-8.222M33.764 42.5v-8.222L39.21 42.5v-8.222m-8.324 0L28.163 42.5l-2.724-8.222");
}

.dc-a4y5vc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 12.694V5.5h37v7.194zm32.889 0L24 22.972L9.611 12.694");
}

</style>
