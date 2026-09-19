<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="no-63f0ce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:shell-terminal" /></template>
<style>
.no-63f0ce {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.5 8.4a4 4 0 0 0-4 4v23.2a4 4 0 0 0 4 4h31a4 4 0 0 0 4-4V12.4a4 4 0 0 0-4-4zM9 23.16l7.72 6L9 35.13v-12zm20.46 11.97h-11");
}

</style>
