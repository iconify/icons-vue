<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="huqzdhv0p"/><path class="saxa20b-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tikkie" /></template>
<style>
.huqzdhv0p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 2.5A21.52 21.52 0 0 0 5.15 34.36L2.5 45.5l11.14-2.65A21.5 21.5 0 1 0 24 2.5");
}

.saxa20b-m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.11 31.71a7.81 7.81 0 0 1-6 2.79h0a7.83 7.83 0 0 1-7.83-7.82v-5.36a7.83 7.83 0 0 1 7.83-7.82h0a7.8 7.8 0 0 1 6 2.82m-17.56 4.84h9.88m-9.88 5.73h9.88");
}

</style>
