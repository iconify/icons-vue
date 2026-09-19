<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ilu_5jbuj"/><path class="br_5rtbxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ning" /></template>
<style>
.br_5rtbxy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.65 11.49a28.64 28.64 0 0 0-26.88 7.6m40.46 0a28.56 28.56 0 0 0-12.51-7.32m-5.34 8.83A18.87 18.87 0 0 0 10.66 26m26.68 0A18.75 18.75 0 0 0 30 21.43");
}

.ilu_5jbuj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m30.1 12.25l-9.3 20.9c-1.5 3.4 5.8 6 6.6 1.9l4.3-22.5c.2-1.4-.9-1.8-1.6-.3");
}

</style>
