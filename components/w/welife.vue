<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hs-fmi5tv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:welife" /></template>
<style>
.hs-fmi5tv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.62 42.5V17.28L24.175 5.5L42.38 17.28V42.5l-15.62-8.02c-1.953-1.001-3.432-.982-5.366 0z");
}

</style>
