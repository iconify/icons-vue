<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xm9uzjeuh"/><path class="jjtn_jabw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:myket" /></template>
<style>
.jjtn_jabw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.166 29.484v-9.278c0-3.047 2.453-5.5 5.5-5.5h.824c3.047 0 5.5 2.453 5.5 5.5l.001 7.87v-7.87c0-3.047 2.453-5.5 5.5-5.5h.825c3.047 0 5.5 2.453 5.5 5.5v9.278M29.54 32.29c-1.297 1.444-3.354 2.296-5.54 2.296s-4.243-.852-5.54-2.296");
}

.xm9uzjeuh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M45.5 24c0 11.874-9.626 21.5-21.5 21.5S2.5 35.874 2.5 24S12.126 2.5 24 2.5S45.5 12.126 45.5 24");
}

</style>
