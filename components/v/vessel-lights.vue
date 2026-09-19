<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="b_qptnu4v"/><path class="f45yud6da"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:vessel-lights" /></template>
<style>
.b_qptnu4v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m21.78 24l-7.124 17.912C7.532 39.095 2.5 32.134 2.5 24S7.532 8.905 14.656 6.088z");
}

.f45yud6da {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M45.5 24c0 10.655-8.635 19.29-19.29 19.29c-2.51 0-4.92-.48-7.124-1.378L26.21 24L19.086 6.088A18.8 18.8 0 0 1 26.21 4.71C36.865 4.71 45.5 13.345 45.5 24m-19.29 0H45.5");
}

</style>
