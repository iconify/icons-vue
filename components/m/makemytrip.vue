<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p9ldgcsef"/><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:makemytrip" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.p9ldgcsef {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.5 18.242c.237-.882 1.473-3.074 2.698-2.857c1.556.275-1.118 11.057-1.118 11.057s6.38-11.152 7.674-10.939c1.149.19-3.31 10.88-2.125 11.165s6.385-10.334 7.305-9.964c.85.342-2.351 9.551-.659 10.001c1.369.364 6.817-10.306 6.817-10.306s-4.477 9.46-1.799 10.565c3.543 1.462 8.207-9.851 8.207-9.851s-5.212 12.512-5.813 14.003a7.65 7.65 0 0 0-.097 6.354");
}

</style>
