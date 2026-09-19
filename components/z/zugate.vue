<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d3h2c346f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:zugate" /></template>
<style>
.d3h2c346f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.203 5.5h25.644L21.858 33.204h14.354l4 9.296H7.788l11.988-27.704h-5.45z");
}

</style>
