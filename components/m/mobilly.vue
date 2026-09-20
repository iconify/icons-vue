<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="r1dks1b_p"/><circle class="ihh0c2wsr"/><path class="y5e_-qrpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mobilly" /></template>
<style>
.ihh0c2wsr {
  cx: 24px;
  cy: 33.468px;
  r: 10.031px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.r1dks1b_p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.688 37.771v-8.614L24 37.781l4.312-8.611v8.611");
}

.y5e_-qrpb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.23 14.694c3.52-2.339 7.52-3.669 11.77-3.669s8.25 1.33 11.77 3.67m-2.25 5.565c-2.847-1.897-6.078-2.956-9.52-2.956s-6.674 1.06-9.52 2.955M9.884 8.908C14.095 6.076 18.904 4.5 24 4.5s9.905 1.576 14.116 4.408");
}

</style>
