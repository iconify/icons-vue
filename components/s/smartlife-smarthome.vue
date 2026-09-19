<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="olthtdbcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:smartlife-smarthome" /></template>
<style>
.olthtdbcf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.15 42.5V19.806L24 5.5l17.85 14.306V39.5a3 3 0 0 1-3 3h-17.8a3 3 0 0 1-3-3V28a5.95 5.95 0 1 1 11.9 0v6.5");
}

</style>
