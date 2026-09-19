<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rzw6xn-lt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ultimate-software" /></template>
<style>
.rzw6xn-lt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.1 16.2h7.8V24h-7.8zm0 15.6h7.8v7.8h-7.8zm7.8-23.4h7.8v7.8h-7.8zm7.8 7.8h7.8V24h-7.8zM12.3 8.4h7.8v7.8h-7.8zM27.9 24h7.8v7.8h-7.8zm-15.6 0h7.8v7.8h-7.8zm-7.8-7.8h7.8V24H4.5z");
}

</style>
