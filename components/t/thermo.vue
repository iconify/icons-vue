<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zn9df9baj"/><path class="erstw1b8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:thermo" /></template>
<style>
.erstw1b8x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.715 11.213v7.119h7.071m-25.571 0h7.07");
}

.zn9df9baj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.715 36.786a5.715 5.715 0 0 1-11.43 0m.001-25.571a5.715 5.715 0 1 1 11.43 0m7.07 7.117a5.715 5.715 0 0 1 0 11.43m-25.571-.002a5.715 5.715 0 0 1 0-11.428M24 29.76a5.715 5.715 0 0 1-5.714-5.714m18.501 5.714H24m-5.714-18.547v12.834m-7.071 5.713h7.07v7.025m11.43-.001V29.76");
}

</style>
