<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g7scycbzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pocketplan" /></template>
<style>
.g7scycbzd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.123 5.5H9.484v37h10.55V31.98h7.089c6.294 0 11.396-5.102 11.396-11.396v-3.687c0-6.294-5.102-11.397-11.396-11.397m8.332 3.619L9.481 29.998");
}

</style>
