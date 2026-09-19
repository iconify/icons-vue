<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="n9dhwtbcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sitedocs" /></template>
<style>
.n9dhwtbcc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.438 34.622H17.903a3.354 3.354 0 0 1 0-6.709h17.889a6.708 6.708 0 0 1 0 13.417H9.972a4.472 4.472 0 0 1-3.873-6.709L20.945 8.906a4.472 4.472 0 0 1 7.746 0l9.037 15.653");
}

</style>
