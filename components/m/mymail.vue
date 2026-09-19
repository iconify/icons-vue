<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vk2s7wbpi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mymail" /></template>
<style>
.vk2s7wbpi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.16 20.22L24 26.05L4.5 18.22v-5A3.68 3.68 0 0 1 8.17 9.5h31.66a3.68 3.68 0 0 1 3.67 3.67v21.66a3.68 3.68 0 0 1-3.67 3.67H8.17a3.68 3.68 0 0 1-3.67-3.67v-8.78");
}

</style>
