<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cagu3xapm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:myhu" /></template>
<style>
.cagu3xapm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.705 6.989v12.465m0 9.092v12.465M5.5 6.989v34.022M28.295 6.989v17.558a7.103 7.103 0 0 0 14.205 0V6.989");
}

</style>
