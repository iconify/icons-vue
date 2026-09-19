<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mfzs_8bxz"/><path class="yfeg5jo_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ocr-tesseract" /></template>
<style>
.mfzs_8bxz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.66 22.059h32.68a3.16 3.16 0 0 1 3.16 3.16v10.2a3.16 3.16 0 0 1-3.16 3.16H7.66a3.16 3.16 0 0 1-3.16-3.16v-10.2a3.16 3.16 0 0 1 3.16-3.16m32.66.004L5.37 9.421");
}

.yfeg5jo_l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.236 28.144h22.338v4.35H17.236zm-8.899 0h4.343v4.35H8.337z");
}

</style>
