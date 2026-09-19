<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qfcm34bit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:wikwok" /></template>
<style>
.qfcm34bit {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 18.195h12.188m14.625 0H43.5m-6.094 0l-6.704 11.61L24 18.195l-6.703 11.61l-6.703-11.61");
}

</style>
