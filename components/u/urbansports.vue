<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p2fgrym4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:urbansports" /></template>
<style>
.p2fgrym4i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25 4.5H10.8v25.8c0 7.3 5.9 13.2 13.2 13.2s13.2-5.9 13.2-13.2V17.7m0-5.3V4.5h-7.6");
}

</style>
