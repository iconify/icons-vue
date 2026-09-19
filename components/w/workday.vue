<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pwv035bgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:workday" /></template>
<style>
.pwv035bgh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.92 16.3C14.13.566 32.69.566 38.08 16.3M9.92 24.082L16.259 43.5l7.484-19.418l7.14 19.418l7.197-19.418");
}

</style>
