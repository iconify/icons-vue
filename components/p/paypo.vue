<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="y2yap8bbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:paypo" /></template>
<style>
.y2yap8bbj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 26.643h15.857V42.5H5.5zm21.143 0H42.5V42.5H26.643zm0-21.143H42.5v15.857H26.643z");
}

</style>
