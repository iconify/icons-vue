<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yjm1qhb_m"/><path class="swa4g0byl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:smartcontrol-alt" /></template>
<style>
.swa4g0byl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.5 8.5c-15.5 0-15.5 31-31 31");
}

.yjm1qhb_m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 35.5v-23a4 4 0 0 0-4-4h-31a4 4 0 0 0-4 4v23a4 4 0 0 0 4 4h31a4 4 0 0 0 4-4");
}

</style>
