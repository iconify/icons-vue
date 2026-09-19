<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qzhhd_x_p"/><path class="dv289sl8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nikke" /></template>
<style>
.dv289sl8f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 30.859V17.141l5.961 13.718V17.141m4.568 0v13.718m4.836 0L21.16 24l3.705-6.813M21.16 24h-1.131m6.993-6.859v13.718m4.837 0L28.154 24l3.705-6.813M28.154 24h-1.132m6.979 0h2.933m1.566 6.859h-4.499V17.141H38.5");
}

.qzhhd_x_p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 42.5h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4m8.276-25.359v13.718");
}

</style>
