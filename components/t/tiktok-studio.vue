<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sk39hpfej"/><path class="xaknajbiv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tiktok-studio" /></template>
<style>
.sk39hpfej {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.895 21.4c-5.827-.005-10.554 4.714-10.56 10.54c-.006 5.827 4.713 10.555 10.54 10.56c5.811.005 10.532-4.69 10.56-10.5V3.5c0 5.827 4.723 10.55 10.55 10.55m5.68 23.45a7 7 0 1 1-14 0a7 7 0 0 1 14 0");
}

.xaknajbiv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.115 40.6c.5.6 1.1.9 2 .9h1.2c1.1 0 2-.9 2-2h0c0-1.1-.9-2-2-2h-1.3c-1.1 0-2-.9-2-2h0c0-1.1.9-2 2-2h1.2c.9 0 1.5.2 2 .9");
}

</style>
