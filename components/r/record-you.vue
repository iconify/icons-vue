<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pcbw2tbdk"/><path class="hjc3w-8xm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:record-you" /></template>
<style>
.hjc3w-8xm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.919 25.59c0 6.582-5.336 11.919-11.919 11.919s-11.919-5.337-11.919-11.92M24 37.509V43.5");
}

.pcbw2tbdk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.03 25.59a7.03 7.03 0 0 1-14.06 0V11.53a7.03 7.03 0 0 1 14.06 0z");
}

</style>
