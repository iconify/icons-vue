<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="snu7usbwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:transfermovil" /></template>
<style>
.snu7usbwq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.22 5.5h25.147l-4.476 18.23M39.367 5.5L21.841 21.892m-9.621 2.472L8.634 42.5H31.97m-6.668-16.043L8.632 42.5");
}

</style>
