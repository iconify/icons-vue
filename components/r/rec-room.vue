<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nlxdijbvv"/><path class="qu7cbv70k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:rec-room" /></template>
<style>
.nlxdijbvv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.837 24.942V12.144M18.03 24.942V12.144m22.86 16.241A28.7 28.7 0 0 1 24 33.881a28.7 28.7 0 0 1-16.89-5.494");
}

.qu7cbv70k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.152 12.145v27.993a2.356 2.356 0 0 0 2.35 2.362h28.981a2.356 2.356 0 0 0 2.361-2.351V12.145zV7.862A2.356 2.356 0 0 1 9.503 5.5h28.98a2.356 2.356 0 0 1 2.361 2.351v4.294");
}

</style>
