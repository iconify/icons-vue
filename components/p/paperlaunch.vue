<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="th586rb_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:paperlaunch" /></template>
<style>
.th586rb_u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 9.5v29a4 4 0 0 0 4 4H24V24h18.5V9.5a4 4 0 0 0-4-4h-29a4 4 0 0 0-4 4m18.5 33L42.5 24");
}

</style>
