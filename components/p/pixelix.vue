<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="aa4-lvb4b"/><path class="s2my15a3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pixelix" /></template>
<style>
.aa4-lvb4b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.375 33.75h9.75v9.75h-9.75zm9.75-19.5h19.5v19.5h-19.5z");
}

.s2my15a3y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.375 4.5h19.5V24h-19.5z");
}

</style>
