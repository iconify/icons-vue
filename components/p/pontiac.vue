<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="u7w53sbwj"/><path class="u0metps2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pontiac" /></template>
<style>
.u0metps2m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m23.982 19.685l-1.186-3.3l-4.078-1.087l3.987-.981l1.312-3.377l1.186 3.3l4.078 1.087l-3.987.982z");
}

.u7w53sbwj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.995 9.108L13.585 4.5s10.42 38.787 10.368 39L34.416 4.545z");
}

</style>
