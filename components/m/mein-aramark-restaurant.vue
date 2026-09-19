<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o_haerbbq"/><circle class="qu59o5bkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mein-aramark-restaurant" /></template>
<style>
.o_haerbbq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 38.17c5.243-2.519 24.758-16.374 11.037-21.035c4.283-.824 7.473-.339 12.903.638c4.857.874 12.415.874 15.06-.26c-1.763 2.267-10.077 7.558-11.588 8.314c-.63 4.66-2.897 8.313-5.039 11.714c-.126-2.268-1.427-7.084-8.187-4.66C12.01 35.272 7.854 37.54 4.5 38.17");
}

.qu59o5bkv {
  cx: 31.408px;
  cy: 12.727px;
  r: 2.897px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
