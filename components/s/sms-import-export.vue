<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dbw70xc0i"/><path class="avuauqm6o"/><path class="kr5--ccnu"/><path class="fyoxiacbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sms-import-export" /></template>
<style>
.avuauqm6o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 28.63h6.644a2.23 2.23 0 0 0 2.228-2.228V15.237");
}

.dbw70xc0i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.364 8.913H8.637A4.137 4.137 0 0 0 4.5 13.049v18.052a4.137 4.137 0 0 0 4.137 4.137h27.636l5.563 5.562a.975.975 0 0 0 1.664-.69V13.05a4.137 4.137 0 0 0-4.136-4.136");
}

.fyoxiacbp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m11.001 24.504l4.127 4.127l4.126-4.127");
}

.kr5--ccnu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m36.999 19.364l-4.127-4.127l-4.126 4.127M24 15.237h-6.644a2.23 2.23 0 0 0-2.228 2.229V28.63");
}

</style>
