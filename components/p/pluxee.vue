<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fvw7q77pj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pluxee" /></template>
<style>
.fvw7q77pj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 5.5h10.278L24 13.722L32.222 5.5H42.5v10.278L34.278 24l8.222 8.222V42.5H32.222L24 34.278L15.778 42.5H5.5V32.222L13.722 24L5.5 15.778z");
}

</style>
