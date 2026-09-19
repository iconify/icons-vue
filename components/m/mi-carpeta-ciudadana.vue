<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vixf7ccbc"/><path class="w5o1kwhjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mi-carpeta-ciudadana" /></template>
<style>
.vixf7ccbc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 5.5h37v37h-37z");
}

.w5o1kwhjs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.667 11.667h24.667v24.667H11.667zm24.666 0l6.167 6.167m-6.167 18.5L42.5 42.5");
}

</style>
