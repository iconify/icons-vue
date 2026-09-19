<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qea8y5dby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:simplethankyou" /></template>
<style>
.qea8y5dby {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 14.81C-.49 26.4 22.37 39.47 24 39.47c1.79 0 24.48-13.07 18.5-24.66c-2.63-4.46-9.5-11.56-18.5 0c-5.38-7.81-13.73-8.42-18.5 0");
}

</style>
